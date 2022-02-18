<h2> C++ Backend Linux and Ubuntu</h2>

<b>(1)</b> TCP Communication</br>
<b>(2)</b> MySQL database</br>
<b>(3)</b> Data format JSON</br>

<h2>MySQL setup</h2>
<p><b>Create a new database</b></p>

```
CREATE DATABASE server;
```

<p><b>Create a table</b><p>
  
``` 
CREATE TABLE server.users (
  `user_id` bigint(255) UNSIGNED AUTO_INCREMENT PRIMARY KEY NOT NULL,
  `username` varchar(14) NOT NULL,
  `email` varchar(50) NOT NULL,
  `password` varchar(250) NOT NULL
);
```
<p><b>Insert a user data</b></p>

```
INSERT INTO server.users (`user_id`, `username`, `email`, `password`) VALUES
(1, 'example', 'example@gmail.com', '1234567890');
```



<h2> Compilation process </h2>
<p><b>You first make sure you have installed cmake > 3.10</b></p>

```
chmod +x build.sh && ./build.sh
```

```
./server
```

```
./client
```


<h2>Server</h2>

![alt text](https://raw.githubusercontent.com/halloweeks/cpp-backend/main/images/Screenshot_20220204-110257.png)

<h2>Client</h2>

![alt text](https://github.com/halloweeks/cpp-backend/blob/main/images/Screenshot_20220204-110238.png?raw=true)

<h2>MySQL</h2>

![alt text](https://github.com/halloweeks/cpp-backend/blob/main/images/Screenshot_20220204-110453.png?raw=true)


<br>
<h2> Improvement for</h2>
<p>If you are professional developer to improve this source code and send me i will update here</p>
<p>Contact Email: halloweeks@gmail.com</p>

<h2>Feedback and report bugs</h2>
<a href="https://github.com/halloweeks/cpp-backend/discussions/">Discussion here</a>

