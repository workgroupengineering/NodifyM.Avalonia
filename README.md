# NodifyM.Avalonia
[![NuGet](https://img.shields.io/nuget/v/NodifyM.Avalonia?style=for-the-badge&logo=nuget&label=release)](https://www.nuget.org/packages/NodifyM.Avalonia/)
[![NuGet](https://img.shields.io/nuget/dt/NodifyM.Avalonia?label=downloads&style=for-the-badge&logo=nuget)](https://www.nuget.org/packages/NodifyM.Avalonia)
[![License](https://img.shields.io/github/license/miroiu/nodify?style=for-the-badge)](https://github.com/miroiu/nodify/blob/master/LICENSE)

A collection of controls for node based editors designed for MVVM.
## About
This project is a refactoring of [Nodify](https://github.com/miroiu/nodify) on the Avalonia platform and is not a 1:1 replica of Nodify, but they have many similarities.
![image](https://raw.githubusercontent.com/MakesYT/NodifyM.Avalonia/master/assets/Kitopia1706512452013.png)

## Usage
### NodifyEditor
 - `Press` and `Hold` -> Move the all show items
 -  Mouse wheel -> Zoom all show items
### Node
 - `Press` and `Hold` -> Move the Node
 - `Press` the Node -> Select the Node
### Connection
 - `Press` and `Hold` the Connector and move to another Connector -> Create a new connection
 - Hold `Alt` and `Click` Connection -> Remove Connection
 - `DoubleClick` Connection -> Split the connection in the double-click position
### PendingConnection
 - `Press` and `Hold` the Connector -> Show connection preview
### Connector
 - Hold `Alt` and `Click` Connector -> Remove all the Connections on the Connector

## Notice
This project is still in its early stages and lacks many events compared to **Nodify**, but it is already available

## Example
#### please see the [NodifyM.Avalonia.Example](https://github.com/MakesYT/NodifyM.Avalonia/tree/master/NodifyM.Avalonia.Example)
#### You can git clone the project and run `NodifyM.Avalonia.Example`