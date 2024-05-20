# 3.13-secrets

run command **aws secretsmanager get-secret-value     --secret-id MalikTestSecret2**

![secretsmanager get-secret-value](https://github.com/mmf2311/3.13-secrets/assets/153518940/bb9ffda8-702b-4a63-92ba-2a7250774228)

run command **aws ssm get-parameter \    --name "/prod/mmf2311"**

![ssm get-parameter](https://github.com/mmf2311/3.13-secrets/assets/153518940/3d1d2838-32d1-4459-b396-e11801cbdda3)

Get secrets from sample code via index.js file

-run npm init to get package.json

-add code **"type": "module",** to package.json file

-add code **console.log(secret)** to index.js file after code **const secret = response.SecretString;**

-npm install @aws-sdk/client-secrets-manager

-run node index.js to get output **{"username":"lfcfan"}**

![node index js](https://github.com/mmf2311/3.13-secrets/assets/153518940/330e5d68-b02b-478b-a444-0c46fb3ec775)

