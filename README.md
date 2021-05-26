# openhab3-ui-carnet-widget
Widget for the openHAB 3 carnet binding

This widget is inspired by the Merzedes Benz integration widget by @muelli1967

https://community.openhab.org/t/mercedes-benz-integration/117795/62

# Prerequisits:
This widget does not need many configs, therefore it uses the predefined channel names of the binding. You should create a car equipement under your model and add all channels as points with predefined names.
All Icons in the subfoler need to be copied to your openHAB 3 conf-folders icon directory : ../conf/icons/classic/*

# Config
The widget takes three configs only:

| Parameter | Description                                          |
|-----------|------------------------------------------------------|
| propLabel      | A Label for the widget (e.g. My Car)                       |
| itemPrefix  | The Name of your car thing, which will be added with default channel names for items, separated by an underscor. |
| pictureUrl  | URL to your car picture |

# Screenshots
![image](https://user-images.githubusercontent.com/5521736/119628988-e4f44c80-be0d-11eb-89d0-28fc4f3a7cca.png)
This is like the widget looks like on the overview page. If Your primary fuelType is 3(Electric), it will show battery level and electric range as well.
After clicking on the widget, it will expand to 
![image](https://user-images.githubusercontent.com/5521736/119664570-c30dc080-be33-11eb-9b1e-9d02eecbc580.png)

Or in Dark Mode
![image](https://user-images.githubusercontent.com/5521736/119664704-e5074300-be33-11eb-9f5e-6a8638aa1366.png)


# Enjoy!
