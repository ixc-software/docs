<a id='1bf25429-8910-4434-808f-a39d197aab8f'></a>

<::A blue icon with rounded corners. The icon features a stylized light blue 'V' shape at the bottom, from which a series of stacked, curved, and slightly twisted light blue shapes rise upwards, resembling a spiral or a stylized letter. The background of the icon is a darker blue with subtle diagonal stripes.: figure::>

<a id='89d60748-8a77-46fe-a813-87994573cb4d'></a>

IXC Softswitch

How to start

<a id='0aa1c236-d367-4c6b-b2aa-53436969752a'></a>

IXC © 2023

<a id='7ed904ba-63b9-46dc-b0d7-05a7a47674a9'></a>

IXC Softswitch V5

<a id='6ac59aa1-2be3-462e-8de1-744526ecea82'></a>

**How to start with your traffic.**

<u>Minimal configuration (LCR, A-Z)</u>

<a id='8d9ffc69-2f00-4e13-a4c9-3255310435b6'></a>

1. Creating your Vendor (Supplier, Carrier) and adding his rates.

<a id='a9a872e4-0005-468b-8ff1-ac2508a3f36f'></a>

Vendor – is the company who is selling destinations and routes to you. In terminology of IXC Softswitch it is formally a Customer who has terminator(s) – the outbound traffic points.

<a id='8ab45401-08bc-4e89-bfb5-bd53c8a06780'></a>

Go to "Customers/Vendors" menu and click on "New Customer" to add your first supplier.
Put a name of your vendor near "Name*" field and click "Create".
You will see "Successful creation" notification.

<a id='df385d52-c84a-487d-86b7-e855915e39f9'></a>

Customer: My Vendor Telecom
---

<a id='399432d0-dbd9-4ac4-a81c-690f83191fe2'></a>

Successful creation.
<::Tabs: General

<a id='84d1dc06-d0cc-4513-ab04-1a6c464ec056'></a>

Next step is to click on “Terminator tariff plans” tab and press on “New tariff plan”. Put a name for
tariff plan and click on “Create”.
You will see “Successful creation” notification.

<a id='a292643b-1027-4044-9436-cd548e7717a7'></a>

Tariff plan: my vendor rates

option Successful creation: [x]

<< Back Price lists General

Upload from file to new ratesheet Upload from file to current ratesheet Create price template

<table><thead><tr><th>Name</th><th>Activation date</th><th>Rows count</th><th>CSV</th><th></th></tr></thead><tbody><tr><td>my vendor rates</td><td>2023-02-27 12:12</td><td>0</td><td>CSV</td><td>Delete</td></tr></tbody></table>

- Active ratesheet

Comments:

<a id='b266e2db-9337-4e58-8b61-19c7eac544ef'></a>

Comments:

[Text input area]

Update comments [Button]

<a id='3c5736ca-044f-4fd0-930b-df280f212d29'></a>

In this page you can manually add some codes and rates if you click on the ratesheet name ("my vendor rates" in this example) or you can use "Upload from file to current ratesheet" tool to upload from file. File format is xls or csv with 3 columns: code;country;price

<a id='c990ea21-37c4-44fb-ba3e-ce0975c25172'></a>

Here is file example in excel.
<table id="2-1">
<tr><td id="2-2"></td><td id="2-3">A</td><td id="2-4">B</td><td id="2-5">C</td><td id="2-6">D</td><td id="2-7">E</td></tr>
<tr><td id="2-8">1</td><td id="2-9">9370</td><td id="2-a">Afghanistan Mobile AWCC</td><td id="2-b">0,086</td><td id="2-c"></td><td id="2-d"></td></tr>
<tr><td id="2-e">2</td><td id="2-f">9371</td><td id="2-g">Afghanistan Mobile AWCC</td><td id="2-h">0,086</td><td id="2-i"></td><td id="2-j"></td></tr>
<tr><td id="2-k">3</td><td id="2-l">9373</td><td id="2-m">Afghanistan Mobile Etisalat</td><td id="2-n">0,074</td><td id="2-o"></td><td id="2-p"></td></tr>
<tr><td id="2-q">4</td><td id="2-r">9378</td><td id="2-s">Afghanistan Mobile Etisalat</td><td id="2-t">0,074</td><td id="2-u"></td><td id="2-v"></td></tr>
<tr><td id="2-w">5</td><td id="2-x">9374</td><td id="2-y">Afghanistan Mobile Salam</td><td id="2-z">0,05</td><td id="2-A"></td><td id="2-B"></td></tr>
<tr><td id="2-C">6</td><td id="2-D">9377</td><td id="2-E">Afghanistan MTN mobile</td><td id="2-F">0,11</td><td id="2-G"></td><td id="2-H"></td></tr>
<tr><td id="2-I">7</td><td id="2-J">9376</td><td id="2-K">Afghanistan MTN mobile</td><td id="2-L">0,11</td><td id="2-M"></td><td id="2-N"></td></tr>
<tr><td id="2-O">8</td><td id="2-P">9379</td><td id="2-Q">Afghanistan Mobile Roshan</td><td id="2-R">0,106</td><td id="2-S"></td><td id="2-T"></td></tr>
<tr><td id="2-U">9</td><td id="2-V">9372</td><td id="2-W">Afghanistan Mobile Roshan</td><td id="2-X">0,106</td><td id="2-Y"></td><td id="2-Z"></td></tr>
<tr><td id="2-10">10</td><td id="2-11">25112</td><td id="2-12">Ethiopia Addis Ababa</td><td id="2-13">0,116</td><td id="2-14"></td><td id="2-15"></td></tr>
<tr><td id="2-16">11</td><td id="2-17">25161</td><td id="2-18">Ethiopia Addis Ababa</td><td id="2-19">0,116</td><td id="2-1a"></td><td id="2-1b"></td></tr>
<tr><td id="2-1c">12</td><td id="2-1d">25111</td><td id="2-1e">Ethiopia Addis Ababa</td><td id="2-1f">0,116</td><td id="2-1g"></td><td id="2-1h"></td></tr>
<tr><td id="2-1i">13</td><td id="2-1j">2519</td><td id="2-1k">Ethiopia Mobile</td><td id="2-1l">0,187</td><td id="2-1m"></td><td id="2-1n"></td></tr>
<tr><td id="2-1o">14</td><td id="2-1p">2519580</td><td id="2-1q">Ethiopia Mobile Addis Ababa</td><td id="2-1r">0,187</td><td id="2-1s"></td><td id="2-1t"></td></tr>
<tr><td id="2-1u">15</td><td id="2-1v">251921</td><td id="2-1w">Ethiopia Mobile Addis Ababa</td><td id="2-1x">0,187</td><td id="2-1y"></td><td id="2-1z"></td></tr>
<tr><td id="2-1A">16</td><td id="2-1B">251922</td><td id="2-1C">Ethiopia Mobile Addis Ababa</td><td id="2-1D">0,187</td><td id="2-1E"></td><td id="2-1F"></td></tr>
<tr><td id="2-1G">17</td><td id="2-1H">251923</td><td id="2-1I">Ethiopia Mobile Addis Ababa</td><td id="2-1J">0,187</td><td id="2-1K"></td><td id="2-1L"></td></tr>
<tr><td id="2-1M">18</td><td id="2-1N">251929</td><td id="2-1O">Ethiopia Mobile Addis Ababa</td><td id="2-1P">0,187</td><td id="2-1Q"></td><td id="2-1R"></td></tr>
<tr><td id="2-1S">19</td><td id="2-1T">25193</td><td id="2-1U">Ethiopia Mobile Addis Ababa</td><td id="2-1V">0,187</td><td id="2-1W"></td><td id="2-1X"></td></tr>
<tr><td id="2-1Y">20</td><td id="2-1Z">251940</td><td id="2-20">Ethiopia Mobile Addis Ababa</td><td id="2-21">0,187</td><td id="2-22"></td><td id="2-23"></td></tr>
<tr><td id="2-24">21</td><td id="2-25">251941</td><td id="2-26">Ethiopia Mobile Addis Ababa</td><td id="2-27">0,187</td><td id="2-28"></td><td id="2-29"></td></tr>
<tr><td id="2-2a">22</td><td id="2-2b">251942</td><td id="2-2c">Ethiopia Mobile Addis Ababa</td><td id="2-2d">0,187</td><td id="2-2e"></td><td id="2-2f"></td></tr>
<tr><td id="2-2g">23</td><td id="2-2h">251013</td><td id="2-2i">Ethiopia Mobile Addis Ababa</td><td id="2-2j">0,187</td><td id="2-2k"></td><td id="2-2l"></td></tr>
</table>

<a id='cd92fe43-c9e9-40e1-bc58-347b85f49f73'></a>

## 2. Create the Terminator of your Vendor.

Terminator – is the outbound traffic point from Softswitch to your Vendor's GW/PBX/Switch/etc.
Go to “Terminators” menu OR you can simply click on the “Back” buttons to navigate back to the Vendor's settings and then use tab “Terminators” there.
Click on “New terminator” to add your first terminator.
Fill in the “Name” and put same to “Tag” fields, then click on “Create”. Please note the “Vendor:” and “Tariff plan:” drop-down lists preselected with required data you created before in p.1
Click on “Create”.

<a id='66f00c4a-7165-4eaa-947d-867b697b54c5'></a>

You should see “Successful creation” notification.

---

Terminator: gw1 out

<a id='b97c8380-5dbb-4e3a-9bb2-ba8a4049f68b'></a>

Successful creation.

<< Back General Softswitches Addresses Gatekeeper accounts

### Obligatory fields
Enable: [x]
Name: gw1 out
Second name:
Tag: gw1 out
Vendor: My Vendor Telecom
Tariff plan: my vendor rates
Priority: 0
Prefix:

<a id='da7f3a1e-d416-4cd7-8ccc-60354af17cbf'></a>

Advance fields (dont use it without needing)

Lines limit: -
Real prefix:
Codec profile: Default
Digits min: 1
Digits max: 16
Signalling profile: - DEFAULT -
Buffer destination: - NONE -
Translate anumber group: - NONE -
LNP list: - NONE -
Translate disconnect code group: - NONE -
Interface group: - DEFAULT -
option Is direct RTP: [ ]
option Is gatekeeper: [ ]
B-number white list: - NONE -
A-number white list: - NONE -
B-number black list: - NONE -
A-number black list: - NONE -
Monitoring profile: - NONE -

<a id='1c76f8ee-4f46-4b17-a84a-b4a80b0e5135'></a>

Update
No calls detected

<a id='e33d0d8c-57fe-406e-aeca-3a00dcd22b8c'></a>

Next step is to add IP address of your terminator. Click on "Addresses" tab, then on "New address".
Enter the IP-address of your Vendor's GW/Switch/PBX near "Host(s)" window, select "Proto" in drop-
down list below, change "Port" if required.

<a id='ee43c2eb-9e9b-44f2-a35a-bc73f5a5cda4'></a>

<::Host(s): 123.213.212.211 (127.0.0.1;127.0.0.5;...)
Proto: sip
Port: 5060
option Translation (# => %23): [ ]
Timeout: 0
Suffix:

Create
: form::>

<a id='a986752a-73b0-4bcd-871d-60bcbc731988'></a>

Please note: default port for h.323 is 1720, and for sip - 5060. Click on "Create". You should see
"Successful creation" notification.
Terminator: gw1 out

<a id='eaca008c-ef81-4489-a98b-04f44bbb848f'></a>

✔ Successful creation.(1 addresses;)
<< Back General Softswitches Addresses Gatekeeper accounts
• New address Show all addresses
<::
Host Port Timeout Suffix Proto
123.213.212.211 5060 0 sip
: table::>

<a id='f2031a11-1ffc-4c6a-8906-67852c0b1d34'></a>

3. Creating your rates and routing for Customer.

<a id='4a017dbd-786c-48bc-8024-5e49d7b03f8b'></a>

Customer – is the company who is buying destinations and routes from you.
We need to do some preparations first and create a price-list for your customer.
Go to Main Page and click on "Manage tariff plans", then click on "New tariff plan", put a "Name" and
click "Create". You will see "Successful creation" notification.
Tariff Plan: my selling rates

<a id='e478e0cf-d7c6-4fc3-8f30-ec21b5996219'></a>

Successful creation.

Price lists General

Upload from file to new ratesheet Upload from file to current ratesheet Manual add to current ratesheet Manual add to new ratesheet Smart upload

<table><thead><tr><th>Name</th><th>Activation date</th><th>Rows count</th><th>CSV</th><th></th></tr></thead><tbody><tr><td>my selling rates</td><td>2023-02-27 13:04</td><td>0</td><td>CSV</td><td>Delete</td></tr></tbody></table>

- Active ratesheet

<a id='b0e4c84d-ef86-4beb-9221-6e72fd8efd2d'></a>

Here you can use “Upload from file to current ratesheet” tool to upload rates from a file. File format is exactly same as you used for vendor before.

<a id='48631062-29dc-474e-a3c5-29c4014723ae'></a>

Alternatively you can add codes manually by clicking on the active sheet name ("my selling rates" in this example), then click on "New price". Put code and price and click "Create". Please note: the rates in this tariff plan should be higher than rates in vendor's price list you created before.

<a id='981794f8-e3fc-4490-a89c-14abdcac93fd'></a>

Once you done with customer's tariff plan the next step is to create route table. Go to "Main Page", click on "Routes Tables", press "New table" and set some Name, click "Create". You will be redirected to the "Build Rules" tab.
Routes table:
New table

<a id='694a5f8b-7b56-4784-8104-105cdab2774f'></a>

Successful creation.

option General: [x]
option Build Rules: [ ]

New Rule

Обзор... Файл не выбран.
file format: Code; Criterion; Limit; Terminator; Prio; Description
Import CSV list

| Enable | Scenario | Destination | Code | Criterion | Lines limit | Terminator | Priority | Description | check_all |
|---|---|---|---|---|---|---|---|---|---|
| | | | | No Items. | | | | | option check_all: [ ] |

-These codes are exist in Trafic disctribution
Delete Checked
Update changes

Hide
Save to CSV

<a id='0897a87a-17c2-4791-8e06-e32eb6db07e7'></a>

Here you need to click on "New rule" and in "Terminator:" drop-down list select the terminator you created before.
New Rule:

<a id='65b4276a-9854-48c6-a620-5ddebcc30b89'></a>

Destinations Codes

Enable: [x]
Code: 1,5...9 / 1;5;...9 / 1 5 9
Criterion: All
Terminator: gw1 out
Priority: -1 (Field is enabled only if Route Priority condition used)
Lines Limit: 0
Description:

<a id='c11359b6-3c3f-448d-bc39-0be903785d2b'></a>

Create

<a id='443da7a1-c7a0-4eb8-902d-22cd096d8bd3'></a>

Press “Create” here to add terminator into route table. You will get “Successful creation” message.
Routes table:

New table

<a id='9edd788b-bf7f-4c55-8582-b199302bcd64'></a>

hide
<::A green notification bar with a checkmark icon and the text "Successful creation.(1 codes: )". Below it are two tabs: "General" and "Build Rules".: interface::> Successful creation.(1 codes: )
General Build Rules
<::A green plus icon next to the text "New Rule".: interface::> New Rule
<::A file upload section with a button labeled "Обзор..." (Browse...) and the text "Файл не выбран." (File not selected.). To the right

<a id='ee72e913-978f-4c0e-8018-9c6707baafca'></a>

Now since we created rates for customer and prepared the route table we can proceed with customer and originator creation.

<a id='fb539187-d6b2-4ef8-ab9d-a63a4756144a'></a>

4. Add a Customer and originator.

<a id='50b485db-04a1-4398-816c-9817b5ec71af'></a>

Go to "Customers/Vendors" menu and click on "New Customer" to add your customer. Fill the "Name" field with the name of your customer, click "Create".

<a id='eb87b1d5-c6c5-40ec-bc42-13eb6a8bc097'></a>

Customer: My customer telecom

<a id='6f7c8518-5233-4997-9a66-90572b7da4f2'></a>

✔ Successful creation.

<::Tabs: General (selected)

<a id='e4df87a8-082a-45f9-80c1-1007f5a6f6c1'></a>

Update

No calls detected

<a id='5a7b53db-c4ba-4193-b79f-51ee4232b345'></a>

Now we can create an originator.
Originator – is the inbound traffic point from customer at your IXC Softswitch.
Go to “Originators” tab and press on “New originator”, put some name to the “Name” and same to
“Tag” fields. Select the route table and tariff plan you created before in appropriate drop-down lists.

<a id='bbcf8de2-a4c3-4df8-827a-3986bf1ee0b8'></a>

Please note the "Customer" drop-down list already preselected with required data you created before in
p.3
Click on "Create".

<a id='25ae396a-366f-446e-8faa-418b1384536b'></a>

Click on "Create".

Originator: customer PRM in

option Successful creation: [x]

<< Back General Softswitches Addresses Gatekeeper accounts

<a id='18206fba-975a-45db-bfec-03c1343e7e40'></a>

# Obligatory fields

option Enable: [x]

Name: customer PRM in

Tag: customer PRM in

Customer: My customer telecom

Route table: my routes

Tariff plan: my selling rates

<a id='c1c4095d-bde0-42cc-bdda-fcbeb51f3c8b'></a>

## Advance fields (dont use it without needing)

Lines limit: -
Digits min: 1
Digits max: 16
Translate anumber group: - DEFAULT -
LNP list: - NONE -
Traffic Distribution Rule: - DEFAULT -
Translate disconnect code group: - NONE -
Signalling profile: - DEFAULT -
Codec profile: Default
Proto: All
option Is direct RTP: [ ]
option Alarm: [ ]
Monitoring profile: - NONE -
Allowed rerouting count: 0

<a id='3564ee3e-81bc-4c36-8b9a-d7f7214fc47c'></a>

Update
No calls detected

<a id='3fda1e70-ce23-437e-8646-90e2e0973095'></a>

You should see “Successful creation” notification and few more tabs.

<a id='ee3705f1-163e-42ed-b0ae-5d05c28cec15'></a>

Next step is to add IP address of your customer so click on "Addresses" tab, then on "New address".
Enter the IP-address of your Customer's GW/PBX/Switch/etc near "Host(s)" window and click on
"Create".
New address:

<a id='e767c6bd-5618-4fe9-b6a0-4e66f38e1f2e'></a>

Host(s): 111.111.111.222
(127.0.0.1;127.0.0.5;...)

option Is block anumber: [ ]
Real prefix:
Prefix:
Anumber:
(1;2;3;4...)
Comment:

Nat: no
Disconnect code: 34
option Translation (# => %23): [ ]
Allowed anumber's length min
Allowed anumber's length max

<a id='eb4d04d5-e6fa-4220-9d7c-e923d4b646f7'></a>

Create

<a id='665783e4-d1e2-456e-ab89-19658e31903d'></a>

You will get “Successful creation” message.

<a id='c2a23733-15a7-41a5-b716-2a8ee0d1efe8'></a>

Then, in order to apply all these settings to the softwitch you need to press "Full reload Config" button at the top-right side of the web-interface.
<::A screenshot of a web interface for IXCBilling 5.8.0. The header shows navigation options like "Main Page", "Management", "Financial Tools", "System Configurations", "Troubleshooting", and "Autotester 1.3". On the far right, there's a user icon and a button labeled "Full reload Config". A red arrow points from the center of the image towards this "Full reload Config" button. Below the header, the date "2023-02-27 13:47" and "Originator: customer PRM in" are displayed. A sidebar on the left lists management categories such as "Originators", "Terminators", "Customers/Vendors", "Leads", "Routes Rules", "Active Calls", "Current Routes", "Routes Tables", "Traffic Distribution Rules", "Destinations", "Origination Codes Manager", "Termination Codes Manager", and "CDR Templates". At the bottom left, there's a checkbox "option Show advanced menu: [x]". The main content area shows tabs for "General", "Softswitches", "Addresses", and "Gatekeeper accounts". Below these tabs, there are buttons "<< Back" and "New address Show all addresses". A table is visible with columns including "Host", "Prefix", "Real Prefix", "Anumber", "Allowed Anumber's length min", "Allowed Anumber's length max", "Is block anumber", "Disconnect Code", "Comment", "Created at", and "Updated at". One row shows "111.111.111.222" under "Host" and "34" under "Disconnect Code". At the bottom of the table, there's a button "Delete Checked".
: screenshot::>

<a id='dadbde16-f534-473b-bd81-fbc23778f57f'></a>

That's it, our configuration is all set, lets check the "Call Path".

<a id='221053c2-dc61-436d-90c7-c5d51b8d4a60'></a>

5. Check if everything is ready.

<a id='b99c37f0-78eb-42c8-8185-235b655448fb'></a>

Call Path tool is like a call simulation to check how the routing will work if IXC Softswitch will receive the call from originator to some exact b-number. Click on "Troubleshooting" icon and then click on "Call Path". Select the originator you just created and put some number to "Bnumber" field (or put a short billing code), then click "Run". As the result, you should get the table with all the info like originator name, billing code and rates to bill that number, routing table name, terminator to which the call will be routed, IP address, etc.

<a id='88bf8de9-3b8f-4d57-bcd0-f12c290ae040'></a>

IXCBilling: 5.8.6 English (GMT+00:00) UTC

Main Page Management Financial Tools System Configurations Troubleshooting Autotester 1.3

2023-02-27 14:02

Troubleshooting
Call Path
Configuration Check
DB Tables
DB Changes
DXC Monitor information
Monitoring profiles
Files
Generation

option Show advanced menu: [x]

Call Path:

Softswitch: IXCSoftswitch
Originator: customer PRM in
Destination: None
Anumber(optional):
Bnumber: 967771262635

Run

<table><thead><tr><th>Originator Name</th><th>Routes table</th><th>Incoming price</th><th>Incoming code</th><th>Terminator</th><th>Terminator Priority</th><th>Price Priority</th><th>Ip</th><th>Outgoing code</th><th>Outgoing price</th></tr></thead><tbody><tr><td>customer PRM in</td><td>my routes</td><td>0.9</td><td>96777</td><td>gw1 out</td><td>0</td><td>-1</td><td>123.213.212.211/sip</td><td>96777</td><td>0.09</td></tr></tbody><tfoot><tr><td colspan="10">Total: 1</td></tr></tfoot></table>

<a id='779407d4-325f-411d-9ea5-a55d5d68196e'></a>

Congratulations! Now you are ready for traffic exchange!

<a id='0975d08e-918a-48d9-99db-10e50412b4e2'></a>

*If you are not getting any results in that table (Total: 0) – something is wrong with your configuration. Please feel free to contact our support. We are glad to help you.