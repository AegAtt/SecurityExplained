### SecurityExplained S-22: Vulnerable Code Snippet - 10

#### Vulnerable Code: 

![Vulnerable Code](../media/code-10.jpg)


#### Solution: 

The code is vulnerable to authentication bypass vulnerability. An attacker can impersonate and login as any user as at the line-10 the code doesn't validate the JWT signature.

##### Code Credits: SonarSource