# Hosting: Google Cloud Functions

## basic example

```ts
import * as functions from "firebase-functions";
import {bot} from "./telegram/bot";
import {webhookCallback} from "grammy";


export const helloWorld = functions.https.onRequest(webhookCallback(bot))

```


