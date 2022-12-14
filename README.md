This is a [Next.js](https://nextjs.org/) project that integrates [Mercury Chat](https://mercurychat.io/), a Cardano wallet communication platform!

This repository serves as an example to showcase how you can embed Mercury Chat into your Cardano DAPP. This example works for both Typescript and Javascript frontends.

<br />

## Integration

To get Mercury Chat in your application, we will need to install the [Mercury Chat React Package](https://www.npmjs.com/package/@mercury-chat/react-chat):

```bash
npm install @mercury-chat/react-chat
```

<b>Note</b>: You can also use yarn, or pnpm to install the package.

After this we need to add this to our application:

```
<MercuryChat />
```

And we're done! Congratulations you have successfully added Mercury Chat to your Cardano Dapp!

<br />

![NextFullscreen](https://user-images.githubusercontent.com/17760631/196579669-c1bd1652-eeb1-4802-b67b-82127fe18700.PNG)

<br />

## Options
There are some options allow you to customize the Mercury Chat experience. Below is an example of the options that can be used. The full option documentation can be found in the [Mercury Chat NPM Page](https://www.npmjs.com/package/@mercury-chat/react-chat)

```
<MercuryChat position={'bottom-right'} hasFullscreen={false} showBackground={false} />
```

<br />

![NextSmallScreen](https://user-images.githubusercontent.com/17760631/196579634-7f626535-b0c7-4a43-93df-1e1f48f600d2.PNG)

<br />

## Running This Repository

If you would like to test our the Mercury Chat functionality within this repo, clone the repo and then run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

And that's it! Play around the ```<MercuryChat />``` component's properties until you have the functionality that you like!
