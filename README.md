<div align="center"> <h1>Corporate-Gifting </h1> </div>

<div align="center"> <img src="imageedit_3_6496006665.png"/>
</div> 
<div align="center"> <h2>Application Name: Corporate Gifting [Scoped] </h2> </div>

<div align="center"> <h4> Description: Corporate Gifting application will be used by the departments of an organisation where managers can appreciate their mentees in the form of E-Voucher with a predefined amount which will be added to the Employee e-wallet. Each employee can order the voucher based on his wallet balance and number of vouchers.The custom application is configured using App Engine Studio, Creating tables and their fields, creating Groups, Configuring Form Layout and List Layout, and creating some dump data for these tables which will help during the whole project implementation.</h4> </div>

<table>
    <tr>
        <td>Field Name</td>
        <td>Field Type</td>
        <td>Comment</td>
    </tr>
</table> 


Employee Number

Auto-generated Number.

Prefix - EMP

E-Wallet Balance

Integer

Read Only

Project/Account

Choice

ABZ Consultancy

PTL India Ltd.

Zone IT Services

YUC Motors

Qwerty Hospitals

Position Level

Choice

Associate, Senior Associate, Technical Lead, Manager, Senior Manager, Director, Delivery Head, HR

E-Wallet Balance Validity

Date

3 months later from the last E-Wallet balance added.

Awards/Appreciations

String

Should contain the list of Awards/Appreciation received with E-Wallet balance.

E-Wallet Budget

Integer

Ready Only

 

 

 

 

2. E-Wallet Request by Managers (Extend from Task table)

 

Field Name

Field Type

Comment

E-Wallet Req Number

Auto-generated Number.

Prefix - EWR

Requested By (Manager)

Reference User table

 

Requested For (Employee)

Reference User table

 

Request Status

Choice

Submitted, Approval Requested, Approved, Rejected, Completed, Cancelled.

 

 

 

 

Groups:

      E-Wallet HR Approver – People who must approve the E-Wallet request by the Manager before it is added to the employee E-Wallet.
      E-Commerce Voucher Agents – HR Agents who would be assigned to the E-Commerce vouchers request submitted by the Managers to help the Employee provide the vouchers offline.
      Shopping/Sports-Wear Voucher Agents - HR Agents who would be assigned to the Shopping vouchers request submitted by the Managers to help the Employee provide the vouchers offline.
      Food Delivery Voucher Agents - HR Agents who would be assigned to the Food vouchers request submitted by the Managers to help the Employee provide the vouchers offline.
 

Form Layout:

      Employee Table
Employee

Employee Number

Email ID

User ID

Mobile Number

First Name

Career Level

Last Name

Project/Account

Name

Active

Position Level

Photo

Manager

 

 

Corporate Appreciations (Form Section)

E-Wallet Balance

E-Wallet Budget

E-Wallet Balance Validity

 

Awards/Appreciations

 

2. E-Wallet Request by Managers Table

 

E-Wallet Request by Managers

E-Wallet Req Number

Request Status

Requested By (Manager)

Opened

Requested For (Employee)

Assignment Group

Watchlist

Assigned To

 

Notes (Form Section)

Additional Comments (Customer Visible) / Work Notes

Activities

 

List Layout:

      Employee Table
Default View:

Employee Number

User ID

Name

Email

Position Level

Manager

Active

 

Corporate View:

Employee Number

User ID

Name

Email

Manager

E-Wallet Balance

E-Wallet Balance Validity

Awards/

Appreciations

 

      2.   E-Wallet Request by Managers Table

Default View:

E-Wallet Req Number

Requested By (Manager)

Requested For (Employee)

Request Status

Assignment Group

Assigned To

Created

</h3>
</div>
 

Data Preparation:

 Create 12-15 records or more for the Employee table with different Position Levels.
 Create 8-10 records or more for the Employee table with HR Position Level. Include them in 4 groups mentioned.
 For Employees, map Managers or above level employees to their manager field.
