<div align="center">


# HWID Spoofer for all games

![1](https://github.com/user-attachments/assets/214d1df0-6000-41cb-a6de-b0f9151bb5c4)


*Hwid Spoofer is a C# application that allows you to change various system identifiers on your Windows computer. This application helps you randomly change some system identifiers on your system.*

> [!NOTE]
> Please note that the use of spoofer tools can lead to changes in your system settings. Always make sure to create a system restore point before making any changes to your system. Use them responsibly! 😊

# Features
<div align="left">

- **HWID Change**: Generates and change a random HWID.

- **PC GUID Change**: Generates and change a random PC GUID.

- **Computer Name Change**: Generates and change a random computer name.

- **Product ID Change**: Generates and change a random product ID.

- **MAC Address Change (Beta)**: Assigns a random MAC address to a specific network interface.

- **All Change**: Randomly changes all system identifiers and the MAC address.

- **Backup Functionality**: The application provides a backup function to store the original values of system identifiers before changes are made, making it easier to revert to the original settings if needed.

## Requirements
- Visual Studio 2022 (.NET Desktop)

# Preview

![Console GUI](https://github.com/MuckPro/bunned/assets/138373919/cb342480-8cc1-40ef-92be-e13b582b34ae)



## Usage

1. Run the application and choose whether you want to change system identifiers randomly (Yes/No).

2. If you select "Yes," you can choose which system identifier(s) you want to change:
   - Hardware ID (HWID)
   - PC GUID
   - Computer Name
   - Product ID
   - MAC Address
   - All of the above


3. The application will guide you through the process of changing the selected system identifier(s).

4. After the changes are made, the application will display the result.

## Resources

- [Source for Generating Random HWID](https://docs.microsoft.com/en-us/windows/win32/cimwin32prov/win32-diskdrive)
- [Source for Generating Random PC GUID](https://docs.microsoft.com/en-us/dotnet/api/system.guid.newguid)
- [Source for Generating Random Computer Name](https://docs.microsoft.com/en-us/dotnet/api/system.guid.newguid)
- [Source for Generating Random Product ID](https://docs.microsoft.com/en-us/dotnet/api/system.guid.newguid)
- [Source for Changing MAC Address](https://docs.microsoft.com/en-us/dotnet/api/system.net.networkinformation.networkinterface)


## Contribution

This project is open-source, and contributions are welcome. If you'd like to contribute by adding features, fixing bugs, or improving the documentation, feel free to create a pull request.
