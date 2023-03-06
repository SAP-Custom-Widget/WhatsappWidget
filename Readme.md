

<img src="https://raw.githubusercontent.com/SAP-Custom-Widget/WhatsappWidget/main/icon.png" width="100">

## SAP Custom Widget: Whatsapp Widget
A SAC Custom Widget to send message to a whatsapp number from SAP Analytics Cloud

![preview](https://raw.githubusercontent.com/SAP-Custom-Widget/WhatsappWidget/main/screenshot.png)

## Installation
To use this widget in your SAP application, follow these steps:

- Download the `WhatsappWidget.json` file from the URLs specified in the webcomponents property of the JSON.
- Go to your SAC Portal, select Analytic Application from the left side bar, and then go to the Custom Widget tab.
- Click on the + icon on the right side and select the `WhatsappWidget.json` file that you downloaded.
- You're done! You can now use it in your app.

## Methods
The widget has the following methods:

### Set Methods

|  Method | Parameter Type  | Description  |
| ------------ | ------------ | ------------ |
| setNumber(number) | integer |  Set Phone Number (without +) |
| setMessage(message) | string |  Set Message to send |
| setCaption(caption) | string |  Set Caption |

### get Methods

|  Method | Return Type | Description  |
| ------------ | ------------ | ------------ |
| getNumber()  | integer |  return Phone Number (without +) |
| getMessage()  | string |  return Message to send |
| getCaption()  | string |  return Caption |

## About
This widget is developed by [Rohit Chouhan](http://linkedin.com/in/itsrohitchouhan "Rohit Chouhan")

