# API Reference

## Overview

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Method

`POST`

## Base URL

```
https://www.example.com
```

## Endpoint

```
/Resources
```

## Sample Request

=== "Headers"

    !!! info ""

        | Key | Value |
        | -------- | ------- |
        | cnx-environment | T2 |
        | cnx-correlationid | 7c3eba71-e214-49f4-a0bb-1b2090351cc7 |
        | Content-Type | application/json |

    !!! info "Field Description"

        | Attributes   | Type | Description |Default Value |
        | --------| ------- | ------- |------- |
        | cnx-environment| string | An environment that is used by third parties for testing purposes.|------- |
        | cnx-correlationid| ------- | ------- |------- |
        | Content-Type| ------- | ------- |------- |

=== "Request Body"

    !!! info ""

        ``` json
            {
            "orderId": "123456789",
            "externalTripId": "abcdef123456",
            "requestedBy": "Online"
            "status": "Booked"
            }
        ```
    !!! info "Field Description"

        | Attributes   | Type | Description |Default Value |
        | --------| ------- | ------- |------- |
        | orderId ^*Required^ |string | Unique ID assigned to the order by cxLoyalty system. <br><br>**Note:** To perform post-sale transactions on an existing order, you must generate a new transit code using this API. In order to do so, you must use the order ID that is returned when the order was created (using the Create Order API).|123456789|
        | externalTripId |string | Unique ID assigned to the cruise booking by third-party system before the booking is confirmed.|abcdef123456|
        | requestedBy |string | Contains the username or the identifier for the user who has logged into the system. |Online|
        | status |enum | contains enum values.<br> <ul>  <li>Booked</li>  <li>Cancelled</li>  <li>n/a</li></ul>|Booked|

        {==

        this space is for formating purpose.
            ++ctrl+alt+del++
        ==}

=== "Parameters"

    | Key    | Value |
    | -------- | ------- |
    |   |     |

## Sample Response

=== "Headers"

    | Key    | Value |
    | -------- | ------- |
    | Content-Type    | application/json    |

=== "Response Body"

    ``` json
    {
     "transitCode": "059eecb6-59e7-4aa4-986c-adf073b628dc"
    }

    ```
