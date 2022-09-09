![TicketSystemV2](https://user-images.githubusercontent.com/91988772/189364589-62fe5ca1-3e38-4ecb-b36a-e9a3fe1db10b.png)


# Global Ticket System V2
Ticket system v2, many new and improved features. Optimized code.

## Dependencies:
-  mongoose => `npm i mongoose`
-  dotenv => `npm i dotenv`
-  discord-html-transcripts => `npm i discord-html-transcripts`

# Instructions:
1) Place the command into your commands folder.
2) Create a new folder in the bot root direcatory and name it "schemas", and than place the schema in there.
3) Change all the paths to the right ones if needed.
4) Place the event into your events folder.

# MongoDB Connection:
- be sure to add this to your ready.js file. Also add `await` before the `execute` in your ready file.
```
    // Add this to the top of the file
    const { connect } = require('mongoose')
    
    // Add this to your ready.js file
    await connect(MONGO_URI)
      .then(() => {
        console.log(`✅ >>> Successfully connected to MongoDB!`);
      })
      .catch((err) => {
        console.log(err);
      });
```

# Preview

## Panel

![image](https://user-images.githubusercontent.com/91988772/189365208-21552160-68e7-4820-a392-b17d611c3577.png)

## Ticket Panel

![image](https://user-images.githubusercontent.com/91988772/189365323-61d11289-a45d-4bc1-b5e5-12eff6155df9.png)

## Closed Ticket Message

![image](https://user-images.githubusercontent.com/91988772/189365398-8d9347dc-e14e-4c22-8845-cf262d0712fa.png)

# Contributing:
> if you want to contribute create a fork of this project and when you are done editing it update the fork and create a pull request.
