# GetAccessTokenHotmail
# ReadHotmailBox

### 1. How to use - Cách sử dụng

```
# Method GET: $"https://ltdsoftware.online/api/ltdsoftware/getaccesstokenhotmail.php?clientId={clientId}&refreshToken={refreshToken}"
# Example: "https://ltdsoftware.online/api/ltdsoftware/getaccesstokenhotmail.php?clientId=9e5f94bc-e8a4-4e73-b8be-63364c29d753&refreshToken=M.C530_BAY.0.U.-CqarvZlaumFZNlgf86vq6Istu*c3YBZeQ7Uj80iEnZthB1iFAwV5cIJvxRX1yZqX7s6bNEbUviwaldld7E9LBKwXt*t6tsL5PuSDWHjai8qjxTb!FnSKNLg5GbBwOt7GL!nxEsmKcRdWLJh3OEHnzJ4IGse!oeaz5wLqqhlPcwmaCDy17hyMZFcfXIB8vo8t2VbdSGRABzwfq4SObSub0WKn56lnbxmk33aoLlbWsAk3gR0UFE7sdwZKyjwvKh*MztB135MMnINFWfN5Sg92bzUaf0TsViq0ripvh1fqCt10KHI1E54yHdal943ZxtAkRP1aVIi3M06AWUWqbgLbpDcvjBv3rABRKyiR8dyflfudBKwNZwmnUF7g4bYkdg29kk9VkD7ZO6*cjLi8ZV5I5dhf6yRCfTxF!CQ3Ofe2KssH"
```

### 2. Result - Kết quả trả về
# Success - Thành công
```
Example - Ví dụ
{
  {"token_type":"Bearer","scope":"https://outlook.office.com/IMAP.AccessAsUser.All https://outlook.office.com/POP.AccessAsUser.All https://outlook.office.com/EWS.AccessAsUser.All https://outlook.office.com/SMTP.Send","expires_in":3600,"ext_expires_in":3600,"access_token":"EwBIA+l3BAAUcDnR9grBJokeAHaUV8R3+rVHX+IAAfFkv7RM1dk5KUCGzkuM2cbz73eHz741N5a84xljWBxJl7hxItIZB+nVXdi0aAtbZBJGZSZSvywTDjn+33Q4q2eQT2Z4Qx/EeDEU6D7jh0eFvqyqNOGM0IGvZYexh3pokcx6FtXQ5pnsMrazAGvjzn06mqXyGQSLIB4+Ni1LU1kj+ILMw+00xmgunWuJzEOU9ztZ7xcHC7iA/fjgHZfQU/BdOSKXgGZSZK38Cj7QfLgcc6LoWv200Iwn9TQ9FP982mItoLzM2kiHFPa8GpyRwi8NbPIlbrmJVEcyfQiEy+WkZRExupHzPwxbEmDkePxcYBjPqpL1qv9fQVaNNu61egoQZgAAEGmPdN8cDBwTUaTPo8DnU1QQAtgDvZ2oi6xy6iPkst5kh22ilDkDABrWnmucFSth20Yx9nSP/uO6JEzyU1Pqegl7WeY84pwZFBa0Qh8lc+eWkoXehpGBeNAPXJcK7YnYGMPyRELTQDriEGkZUvdkoTQxlbvXmu3bSwB2cBRwNpx3RLj0o0uLk3T8ou34rFgrlm6pJd4fMKfIzWNIRZm/Y9pEsPY+IaYlcGvl7ccZC/gGlj1k44eyr54CG+h5WwavHDfytya9o6NcOqOQf8Wrw4usYgUzWma1l8aCl+Y6XobWLi/svbbcZWfXnsc22wbOIRRwMLwa+mL8TgHt8SeOvv8vLltfw9av+YP4au+Qao9+sifSYgOM4YMJMV8lub0Bs8YsWHHnmyYxE5XE1UaqlzlMsPYG7mVeBqPgB7dNxJzwSMC58E/A+RYsUSr2yKBWaRO2QWLvar+1zHxH6qf1cvNl4NKQiWuj3UcAix0+gpC3veR/H5UsJKHU+O35yf71Gyy3yd6Cbdw0HHmFjUm13rolviuGnrPXkcrMX+tcab/W9Sm+5LxTwQo6hLLYUeFWmFhjwESdGkv971lKOwlEpay3mXrplFVkVTBlz5g4IDZZkIih6UrnRPcEZ+mZKf9EkgopXAw1F0+UU/yeX70AS5xnUKOQyRuIB5a/T+rJ1dh496s6O3Tang+61Ojuy5Kx4mdre7mxIK0Be6OkVfhqUDTHOz4C"}
}
```

# Fail - Thất bại
```
Example - Ví dụ
{
    ""
}
```
