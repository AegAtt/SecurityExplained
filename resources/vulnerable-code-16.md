### SecurityExplained S-28: Vulnerable Code Snippet - 16

#### Vulnerable Code: 

![Vulnerable Code](../media/code-16.jpg)


#### Solution: 

The code is vulnerable to XXE attack because the use of the `LIBXML_NOENT` enables the external entity loading in php8.

Similar Issue: https://blog.sonarsource.com/wordpress-xxe-security-vulnerability

##### Code Credits: SonarSource