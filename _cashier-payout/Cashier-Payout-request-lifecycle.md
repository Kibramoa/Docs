---
title: Payout Request Life-cycle
position_number: 1
parameters:
  - name:
    content:
content_markdown: |-
   When the API is correctly built and accepted the Kibramoa system will send back a URL with the Kibramoa cashier to process payouts.
   
   Sequence diagram with the comunication process between systems:
   
   ![kibramoa cashier sequence](/images/Payout_flow.png)

   {: .warning }
   **Note:** Merchant system must always respond to notification with Http 200 code, otherwise Kibramoa API will retry at least 10 times.
---