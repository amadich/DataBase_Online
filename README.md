# DataBase_Online
A new and interesting idea, creating a website with react, php and mySQL, and connecting to hosting databases outside GitHUB 🤯
![image](https://user-images.githubusercontent.com/74735976/218319315-ce71125f-dad3-4a5b-869f-fcd4df2be729.png)
###
In this way, we access the files on the hosting to complete the connection with the databases and thus send us information
```js
useEffect(() => {
    console.log(1);
    const urllocal = "https://hostname.com/server/mySQL.php";
    Axios.get(urllocal).then((response) => {
      setmyinfo(response.data);
    })
  }, [])
```
