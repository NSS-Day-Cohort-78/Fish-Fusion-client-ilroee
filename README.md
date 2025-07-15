# Fish Fusion Group Project

In this project, you are going to build a purchasing pipeline for a bargain fish restaurant in your city. It is **crucial** that your team reads all of the requirements and builds an algorithm with comments before you write a single line of code.


## Getting Started

Each teammate should follow these instructions.

1. Click the green **Code** button above.
2. Make sure that **SSH** is chosen for the connection string _(e.g. it should start with git@github.com...)_.
3. Copy the connection string
4. Go to/open a terminal and type `cd ~/workspace` then press **Enter**.
5. Type in `git clone ` and paste the connection string at the end. Then press **Enter**.
6. This process will create a new sub-directory under `workspace`. Type in `ls` and then press **Enter** to see that new directory.
7. Use the `cd` command to navigate to that directory.
8. Use the `code .` command to open the project in Visual Studio Code.

## Guidelines

- A VSCode extension your team can use to collaborate is [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- LLM usage _(Copilot, ChatGPT, Claude, etc…)_ is not to be used for this project. It is your opportunity to collaboratively build your analytical and algorithmic thinking.
- Building a sequence diagram to visualize your algorithmic thinking is recommended.
- Don’t dominate the conversation and try to impress your will upon your teammates. Collaborate.
- Don’t remain silent and let your teammates do all the work. Collaborate.
- Use the logic and mechanisms covered in this book and the Foundations Course. We should not see array methods, spread operators, or any other advanced JavaScript mechanisms.
  
## Project Overview

There are 3 different actors in this system, and you will write functions in multiple modules of code to have them share data, and in the end, the restaurant will make its final purchases.

1. **Fishing Boat** - This is the source of the fish. The boat catches the fish and makes the fresh catch available to purchasers.
1. **Fishmonger** - The fishmonger purchases fresh fish off the boat, and head chefs around the city visit every morning to get fish for their daily menus.
1. **Fish Restaurant** - The chef at fish restaurant purchases fresh fish from the fishmonger every day. To keep her prices low, she purchases lower cost food and combines them in tasty ways that people might not expect.

## Requirements

| #   | 🐡 Fish Fusion 🍣 |
| --- | --- |
| 1   | [The Fishing Boat](./requirements/FISHING_BOAT.md) |
| 2   | [The Monger](./requirements/FISH_MONGER.md) |
| 3   | [The Restaurant](./requirements/RESTAURANT.md) |
| 4   | [Menu Example](./requirements/EXAMPLE_OUTPUT.md) |
| 5   | [Advanced Iteration](./requirements/MAP_METHOD.md) |
