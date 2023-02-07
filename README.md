# Webscraping_json_dynamic_table

Hello connections :stuck_out_tongue_winking_eye:	


Want to know how to webscrap the dynamic table you are in the right repository :monocle_face:


DIFFERENCE BETWEEN DYNAMIC AND STATIC TABLE:

In a static data column, users can manually enter text data.

In a dynamic data column, the data is displayed as retrieved from any mapping, such as context data or API response.

Take any website Click Inspect>Networks>FetchXhr

I took the example "https://www.forbes.com/real-time-billionaires/#76c970fa3d78"

Then Click Inspect>Networks>FetchXhr

Reload your website. Then you shall see some files generating over it

LIKE THIS, (I wanted to scrap the table so i located the json file in it)

![image](https://user-images.githubusercontent.com/68784899/217184648-550ce369-0aae-4592-826a-57d4c8706f78.png)

Double-Click the one which i represented in red-rectanglar form

![image](https://user-images.githubusercontent.com/68784899/217186712-3054e5ca-a31f-4c3b-a100-fc2110e6c93e.png)

Then copy that link and use it in url variable which i have displayed in my notebook

Then i just saved that file by Ctrl+S as "web.json"

Then i have read it and deleted the count column as it is not needed to us

After that, i parsed it by writing the lambda function.

Hope this helped you :smile:

