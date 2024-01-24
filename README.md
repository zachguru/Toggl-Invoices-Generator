# Toggl Invoice Generator

![Toggl Logo](https://www.cpapracticeadvisor.com/wp-content/uploads/sites/2/2022/07/27659/logo_1_.59f9ec13e81a7.png)

This is an Invoice Generator for Toggl entries. This application uses the **since** and **until** fields in the env.yaml file to determine the date range for invoice generation. It's also integrated with the **Wise API**, allowing it to calculate the current USD to EUR exchange rate, should that be necessary. The env variables are openly accessible; simply modify the **env.yaml** file with your Toggl details, and the generator will function seamlessly.

## How to run?

To run this invoice generator, do the following:

- Clone repository
- Install node packages from root folder with

```
yarn install
```

- Modify .env.yaml file as per your need
- Run the below command to generate the invoice (FROM ROOT FOLDER!!!)

```
ts-node src/pdf.ts
```

Once you execute this command, a message will appear in the terminal stating _Done: invoice.pdf is created!_. This indicates that a file named invoice.pdf has been generated and can be found in the root folder.
