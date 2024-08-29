## In ModStartCMS v8.8.0, I found OpenRedirect Vulnerability in param "redirect" of login feature </br>

ModStart CMS v8.8.0: https://github.com/modstart/ModStartCMS</br>
## Reproduce bug:</br>
Step 1: Access to https://cms.demo.tecmz.com/login?redirect=https%3A%2F%2Fgoogle.com and log in to an account. </br>
![Alt text](ModStart2.png)
</br>Step 2: Website redirect to https://google.com </br>
![Alt text](ModStart1.png)

I hope you know the impact of open redirect and more info refer
https://cwe.mitre.org/data/definitions/601.html
