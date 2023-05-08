# Troubleshooting Common Angular Projects

## Running Blank Screen or Components not Switching

If your Angular project is running but the components are not being displayed, check the following:

- [ ] If your **index.html**'s base href is properly set
- [ ] If your **package.json**'s script includes the command to build towards the docs file.
- [ ] If you have a **404.html**


## **index.html**

The **index.html**'s base href should have a "**/**" or forward slash.


![image](https://user-images.githubusercontent.com/111161441/236477471-b771134a-6987-4b86-a3ae-73c7bfe9aec2.png)

## **package.json**

The **package.json**'s script should include the following code:

```sh
    "docs": "ng build --output-path docs --base-href /",
```

Insert it within the script and save it. It should look like this:

![image](https://user-images.githubusercontent.com/111161441/236478004-0c78b896-725c-48af-93f6-eab1baea063b.png)

## **404.html**

If you do not have a **404.html** file, navigate towards your docs folder

![image](https://user-images.githubusercontent.com/111161441/236485196-11b18888-59ce-4125-b2be-b315a462f2ba.png)
