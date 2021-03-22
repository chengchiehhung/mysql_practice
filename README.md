# 第五週作業

## 要求三
1. INSERT INTO user (name, username, password) VALUES ("Jeff", "ply", "ply");
![image](Screenshots/1.png)
2. SELECT * FROM user;
![image](Screenshots/2.png)
3. SELECT COUNT( * ) FROM user;
![image](Screenshots/3.png)
4. SELECT * FROM user ORDER BY time DESC;
![image](Screenshots/4.png)
5. SELECT * FROM user ORDER BY time DESC LIMIT 1,3;
![image](Screenshots/5.png)
6. SELECT * FROM user WHERE username = 'ply';
![image](Screenshots/6.png)
7. SELECT * FROM user WHERE username = 'ply' AND password = 'ply';
![image](Screenshots/7.png)
8. UPDATE user SET name = '丁滿' WHERE username = 'ply';
![image](Screenshots/8-2.png)
9. DELETE FROM user;
![image](Screenshots/9.png)
## 要求四
1. SELECT name,content FROM user JOIN message ON user.id = message.user_id;
![image](Screenshots/11.png)
2. SELECT name,content FROM user JOIN message ON user.id = message.user_id AND user.username = 'ply';
![image](Screenshots/12.png)
