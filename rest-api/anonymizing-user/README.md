# Anonymize or delete user data

This example shows how you can anonymize or delete information about users and their conversations. The script does not remove the user associated with the given app ID from the TalkJS database, but makes sure that the user cannot be recognized anymore, neither by name nor by messages sent by that user.

> [!TIP]
> [Download this example project as a zip file](https://github.com/talkjs/talkjs-examples/releases/latest/download/rest-api.anonymizing-user.zip)

## Usage

This example contains a TypeScript version and a JavaScript version of the same script. In order to use it, first edit data inside the script:

- `appId` and `secretKey`, both can be found in the [TalkJS dashboard](https://talkjs.com/dashboard/)
- `userId`
- `cleanupOnlyUsersMessages` - if set to true, only messages sent by that user will be anonymized. This setting is useful when the conversation is important and needs to be inspected in the future.
- `cleanupConverstions` - clears conversation metadata such as `photoUrl` and `custom` if set to true. 

The next step is running the script:

```bash
node anonymiseUser.js
```

or for a TypeScript version of the script:

```bash
ts-node anonymiseUser.ts
```

In order to compile the TypeScript version of the script to JavaScript run the following command:

```bash
tsc --target esnext anonymiseUser.ts
```