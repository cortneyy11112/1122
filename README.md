# 1122
1221
<?php

// 连接数据库
$db = new PDO('mysql:host=localhost;dbname=mydatabase', 'username', 'password');

// 清空数据表
$db->query('TRUNCATE TABLE users;');

// 关闭数据库连接
$db = null;

echo "数据表已清空。";

?>
