# _Hair Salon_

#### _A C# MVC Application, friday code review. March 20, 2020_

#### By _**Jeremy Kale Padot**_


## Description

_An MVC application for Eau Claire's Salon. This application will allow the salon owner to keep track of stylists and clients. Each stylists will have a unique set of clients that match their speciality. _

![Landing Page Preview]()



## Behavior Driven Project Specifications

| Behavior | Input | Output |
|:---|:---:|:---:|
| Application will display a home page in which the user may choose to view or create a new Stylist or Add Client to an existing stylist | Home | "New Stylist", "View Stylists", "Add Client" |
| Application will suggest to redirect to Home Page if no Stylists have been added | Click: "View Stylists" | "No stylists have been added yet" Link: Return Home |
| Application will allow user to select view Stylists and recieve a list of Stylists | Click: "View Stylists" | "Stylists:" "Stylist1", "Stylist2", OR "Add New Stylist"  |
| When user clicks "Add Stylist", they are directed to a for to add new stylist  | Click: "Add Stylist" | "Add A New Stylist" Name: "Input Name" |
| When a User adds a new Stylist Name they are directed back to the Stylists Index page | Name: "Input Name", Click: Submit | Stylists: "Haru" |
| When user clicks "Add Client" they will be directed to a client form | Click: "Add new Client | "Add New Client:" Name: "Input Name" |
| In "Add New Client", User will need to assign Client to a Stylist | Click Stylist Dropdown: "Name" / Click: " "Add New Client"   | "Clients" Client: "Name" / Stylist: "Name" |



## Setup/Installation Requirements

In your computer's terminal:

1. Navigate to where you want this application to be saved, i.e.:
```sh
cd desktop
```
2. Clone the file from GitHub with HTTPS
```sh
git clone https://github.com/kalepadot/HairSalon.Solution.git
```
3.  Enter into the new file directory
```sh
cd HairSalon.Solutions
```
4. Enter the program file
```sh
cd HairSalon/
```
5. Restore
```sh
dotnet restore
```
6. Build
```sh
dotnet build
```
7.  Start the program
```sh
dotnet run
```
8. Open in your browser by clicking
```sh
http://localhost:5000
```


## Known Bugs

_No known bugs at this time._

## Support and contact details

_Have a bug or an issue with this application? [Open a new issue](https://github.com/kalepadot/HairSalon.Solution/issues) here on GitHub._

## Technologies Used

* C#
* .NET 2.2
* Terminal
* Git
* VS Code
* Macbook Pro
* MVC
* Mr. Squiggles
### License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2020 **_Jeremy Kale Padot_**