# Dr. Sillystringz's Factory

#### An app to help manage machines and engineers within the factory

#### By Scott Hutley

## Technologies Used

* _C#_
* _.Net 5.0_
* _.Net ef_
* _ASP.NET Core_
* _NuGet_

## Description

Dr. Sillystringz has a factory that makes hot garbage all day long. But he still needs to know what machines he has in his factory and, perhaps more importantly, who he's hired to maintain those machines so they can routinely produce the hottest garbage each and every day. 

## Setup/Installation

#### Technology Requirements

* .NET 5
* VS Code or other text editor
* MySQL Workbench

#### Cloning and Database Creation

* Clone this repository to your desktop
* Open with text editor and navigate into Factory.Solution/Factory folder
* Create an appsettings.json file
* Add the following code to the appsettings.json:
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=scott_hutley;uid=root;pwd=YOUR_PASSWORD;"
  }
}
```
* Replace "YOUR_PASSWORD" in the above code with your own personal MySql password
* Open a Windows Powershell terminal (or Mac equivalent)
* In that terminal run *mysql -uroot -p<YOUR_PASSWORD>* (again, replacing with your actual password)
* Open MySQL Workbench
* Return to your text editor
* Navigate to the HairSalon.Solution/HairSalon folder level (if you are not already there)
* Run *dotnet ef migrations add Initial*
* Run *dotnet ef database update*
* Run *dotnet restore*
* Run *dotnet build*
* Run *dotnet run* to use the app!
(note: If dotnet run does not auto-generate a browser page, you can manually enter http://localhost:5000 into your web browser)

## Known Bugs

* _No know issues_

## License

_[MIT](https://opensource.org/licenses/MIT)_

Copywrite(c)2021 Scott Hutley

## Contact Information

Scott Hutley: scotthutley1@comcast.net