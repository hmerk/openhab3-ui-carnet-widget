# openhab3-ui-carnet-widget
Widget for the openHAB 3 carnet binding

This widget is inspired by the Mercedes Benz integration widget by @muelli1967

https://community.openhab.org/t/mercedes-benz-integration/117795/62

# Prerequisits:
This widget consists of two parts, the dashboard and the details view. You can add them in combination or use just one part individually.
To keep configuration simple, the predefined channel names of the binding. You should create a car equipement under your model and add all (check advanced) channels as points with predefined names.
All Icons in the subfoler need to be copied to your openHAB 3 conf-folders icon directory : ../conf/icons/classic/*

# Config
The widget takes four config params only:

| Parameter   |           | Description                                          |
|-------------|-----------|-------------------------------------------|
| propLabel   | optional  | A Label for the widget (e.g. My Car)                       |
| carGroup    | mandatory | The equipement/group name of your car items |
| itemPrefix  | mandatory | The Name of your car thing, which will be added with default channel names for items, separated by an underscor. |
| pictureUrl  | optional  | URL to your car picture if you don't want to use pictures retreived by the binding |

# Screenshots
Like in a real car dashboard, some of the icons only appear if there should be a warning
![dashboard](https://user-images.githubusercontent.com/5521736/124281285-de15d380-db49-11eb-9b41-bd8570743769.PNG)
This is like the widget looks like on the overview page. If Your primary fuelType is 3(Electric), it will show battery level and electric range as well.
After clicking on the widget, it will expand to 
![image](https://user-images.githubusercontent.com/5521736/124281402-f7b71b00-db49-11eb-8a3d-c4b435de967c.png)
![image](https://user-images.githubusercontent.com/5521736/124281538-17e6da00-db4a-11eb-9f8e-5a30f8c9b9cf.png)
![image](https://user-images.githubusercontent.com/5521736/124281604-2af9aa00-db4a-11eb-9a37-818e3fe63e2e.png)
![image](https://user-images.githubusercontent.com/5521736/124281701-45cc1e80-db4a-11eb-9a4d-b8d744f81f97.png)






# Enjoy!
