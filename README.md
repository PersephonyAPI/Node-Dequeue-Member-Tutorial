# Node Dequeue a Member Tutorial

This project serves as a guide to help you build an application with Persephony. Specifically, the project will:

- Remove a call from a call queue and interact with the dequeue call   

## Setting up your new app within your Persephony account

To get started using a persephony account, follow the instructions [here](https://persephony-docs.readme.io/docs/getting-started-with-persephony).

## Setting up Dequeue Member Tutorial

1. Install the node packages necessary using command:

   ```bash
   $ yarn install
   ```

2. Configure environment variables (this tutorial uses the [dotenv package](https://www.npmjs.com/package/dotenv)).

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | accountId              | Account ID which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard                                                         |
   | authToken              | Authentication Token which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard                                               |

3. Provide a value for the `queueuId` and `callId`. More about queues can be found [here](https://docs.persephony.com/reference/queues-1) and more about calls can be found [here](https://docs.persephony.com/reference/calls-1)

## Runnning the Tutorial

1. Run the application using command:

   ```bash
   $ node dequeueMember.js
   ```

