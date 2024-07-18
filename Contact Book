contacts = {}
def add_contact(name, phone):
    contacts[name] = phone
    print(f"Contact {name} added successfully!")
def view_contacts():
    if contacts:
        print("List of Contacts:")
        for name, phone in contacts.items():
            print(f"{name}: {phone}")
    else:
        print("No contacts in the book.")
def search_contact(name):
    if name in contacts:
        print(f"Contact {name}: {contacts[name]}")
    else:
        print(f"Contact {name} not found.")
def delete_contact(name):
    if name in contacts:
        del contacts[name]
        print(f"Contact {name} deleted successfully!")
    else:
        print(f"Contact {name} not found.")
while True:
    print("\nContact Book Menu:")
    print("1. Add Contact")
    print("2. View Contacts")
    print("3. Search Contact")
    print("4. Delete Contact")
    print("5. Exit")

    choice = input("Enter your choice (1/2/3/4/5): ")

    if choice == '1':
        name = input("Enter the contact's name: ")
        phone = input("Enter the contact's phone number: ")
        add_contact(name, phone)

    elif choice == '2':
        view_contacts()

    elif choice == '3':
        name = input("Enter the contact's name to search: ")
        search_contact(name)

    elif choice == '4':
        name = input("Enter the contact's name to delete: ")
        delete_contact(name)

    elif choice == '5':
        print("Contact Book exiting. Goodbye!")
        break

    else:
        print("Invalid choice. Please enter a valid option (1/2/3/4/5).")
