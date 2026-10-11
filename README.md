# 📒 Address Book Management System using C

A simple **Address Book application** is a C based application designed to manage contact information efficiently.
The application allows users to add, list, search, edit, and delete contacts.  
This project demonstrates structured programming, file handling, and input validation in C.

## Introduction

Address Book is a console-based application written in C. It is designed to keep track of contact details, including:

- Contact names
- Telephone/mobile numbers
- Email addresses
- Gender
- Location

## Aim

The aim of the Address Book project is to provide a simple, menu-driven way to manage contact information. Users can add, view, search, update, and delete contacts, and save the contact list to a data file.

## Features

- **Add Contact:** Add a new contact to the list.
- **Edit Contact:** Modify an existing contact's name, phone number, or email address.
- **Search Contact:** Search for a contact and access its associated details.
- **List All Contacts:** Display all contacts stored in the list.
- **Delete Contact:** Remove a contact after confirmation.
- **Save Changes:** Save the contact list to a data file.
- **Exit:** Exit the application, with options to save, discard, or cancel.

## User Interface

The application uses a menu-driven console interface. The menus described in the project include:

- Main menu
- Add contact menu
- Edit contact menu
- List all contacts menu
- Search contact menu
- Delete contact menu
- Save changes
- Exit from the application

When editing a contact, the user can modify the contact name, phone number, or email address. Delete and save operations use confirmation prompts.

## Data File Format

The project specifies a human-readable and editable data file. The example format shown in the project is:

```text
#2#
SMITH:PHONE:+9197234845:::::
SMITH:EMAIL:smith@xyz.com:::::
SINGH:PHONE:++918885248152:::::
SINGH:EMAIL:singh152@zxy.co.in:::::
```

In this example, contact details are stored as text records. Phone numbers and email addresses are represented by separate records for each contact.

## Technologies

- **Programming language:** C
- **Interface:** Console / menu-driven
- **Data storage:** Human-readable text data file

## How It Works

1. The user opens the application and selects an option from the main menu.
2. The user can add a contact or manage an existing contact.
3. Contact details can be searched, listed, edited, or deleted.
4. The user can save changes to the data file.
5. The user can choose to save and exit, discard changes, or cancel the exit operation.

## Project Scope

This README is based on the supplied project presentation. The presentation describes the intended features and sample data-file format, but does not specify build commands, exact source files, or implementation details. Those details can be added once the C source code is available.

##
Implemented by Tharis Selvaraj, Advanced Embedded Systems Trainee, Emertxe Information Technologies, Bengaluru.


