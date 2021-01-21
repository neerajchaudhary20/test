# test


This is the first commit. Initializing the repo.



# Sample App Name's
Nextjs-symblai-demo
  
##  Introduction 
Symbl is a comprehensive suite of APIs for analyzing natural human conversations - both for your team’s internal conversations and of course the conversations you are having with your customers. Built on our Contextual Conversation Intelligence (C2I) technology, the APIs enable you to rapidly incorporate human-level understanding that goes beyond simple natural language processing of voice and text conversations.

## Pre-requisites
To get started, you’ll need your account credentials and Node.js installed (> v8.x) on your machine.Your credentials include your appId and appSecret. You can find them on the home page of the Symbl.ai platform.

![App ID](https://docs.symbl.ai/images/credentials-faf6f434.png)


### Environment variables
After you sign up on the Symbl.ai platform you copy your APP_ID and APP_SECRET, you need to set them up under `.env` file in this repo

```
APP_ID=
APP_SECRET=
```

    
## Deploying

To run app locally , add credentials to `next-config.js` file filling in `APP_ID` and `APP_SECRET` variables.

```javascript
module.exports = {
  env: {
    APP_ID: '',
    APP_SECRET: '',
  },
}
```

run `yarn` or `npm install`. To run the app, use `yarn dev`

Relevant docs section:

- [Getting started with Symbl](https://docs.symbl.ai/#getting-started)
- [API overview using Postman](https://docs.symbl.ai/#postman)
- [Authentication](https://docs.symbl.ai/#authentication)

How Tos are available [here](https://docs.symbl.ai/#how-tos)

In this app represented are the following

- Symbl Node SDK (Check out `api/call` file)
- REST Telephony API (`/phone` page)
- Conversational API (`/conversations` page)
- Async Audio API (`/audio` page)
- Async Video API (`/video` page)
- Async Text API (`/text` page) - Coming soon
- Symbl react elements package available [here](https://www.npmjs.com/package/@symblai/react-elements)



## Conclusion

### Community

If you liked our integration guide, please star our repo!

If you have any questions, feel free to reach out to us at devrelations@symbl.ai or through our Community Slack at [https://developer.symbl.ai/community/slack](https://developer.symbl.ai/community/slack)

This library is released under the [MIT License][license]

[Signup for free](https://platform.symbl.ai)
