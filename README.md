# DataBase_Online
A new and interesting idea, creating a website with react, php and mySQL, and connecting to hosting databases outside GitHUB 🤯

![image](https://user-images.githubusercontent.com/74735976/218321164-5844dae2-07ba-407e-a4d6-edf0d433dabe.png)

###

![image](https://user-images.githubusercontent.com/74735976/218319315-ce71125f-dad3-4a5b-869f-fcd4df2be729.png)
###
In this way, we access the files on the hosting to complete the connection with the databases and thus send us information
```js
useEffect(() => {
    
    const url = "https://hostname.com/server/mySQL.php";
    Axios.get(url).then((response) => {
      setmyinfo(response.data);
    })
    
  }, [])
```
# Warning

Many people will see this error, and the reason is the combination of https and http
You must make sure that you are working on paid https hosting

![image](https://user-images.githubusercontent.com/74735976/218320377-29b095e3-c6a9-4993-9032-9725ea5e84ae.png)
![image](https://user-images.githubusercontent.com/74735976/218321569-0929cb55-05a9-4ec0-984e-bee5fba801af.png)

###

# make sure your hosing Using Public PHP {phpmyadmin} :
![image](https://user-images.githubusercontent.com/74735976/218321732-f12b91a1-a1e6-4e1d-a654-98c7387da24d.png)

# Enjoy 🌹
