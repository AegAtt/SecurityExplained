### SecurityExplained S-25: Vulnerable Code Snippet - 13

#### Vulnerable Code: 

![Vulnerable Code](../media/code-13.jpg)


#### Solution: 

The code is vulnerable remote code execution vulnerability via Path Traversal. Payload like this works: ?dir=<h1>.</h1>.<h1>/</h1>.<h1>.</h1>/<h1>.</h1>./user/profile.png

##### Code Credits: Octagon Networks