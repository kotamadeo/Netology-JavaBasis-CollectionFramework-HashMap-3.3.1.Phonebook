# **Задача № 1 Телефонный справочник**

## **Цель**:
1. Создать программу,  представляющую собой телефонную книгу. Один контакт может входить в несколько групп. Например, если вы работаете со своим другом, то он будет в группах "Друзья" и "Работа". Должна быть возможность создания групп и контактов, добавления одного контакта в несколько групп. 
2. Создать систему классов:
* **Contact** - класс, описывающий контакта;
* **PhoneBook** - класс, описывающий телефонную книгу.
3. Иметь возможность поиска контактов по группе;
4. Иметь возможность поиска контакта по номеру (одну из этих двух последних операций можно сделать перебором);
5. Продемонстрировать работу методов в классе **Main**.

### *Пример*:
``` Пример 1
Эта программа эмулирует работу телефонной книги!
Возможные команды программы:
0 или выход: выход из программы.
1: переименовать название телефонной книги.
2: добавить контакт в телефонную книгу.
3: добавить группу в телефонную книгу.
4: добавить контакт в группу.
5: удалить контакт из группы.
6: удалить группу вместе с контактами.
7: вывести телефонную книгу на экран.
8: вывести список контактов в заданной группе на экран.
9: найти контакт по номеру телефона.
10: найти контакт по имени и номеру телефона.
11: найти контакт по фамилии и номеру телефона.
12: найти контакт по фамилии и имени.

1
Чтобы переименовать телефонную книгу введите новое название
Мой список контактов

2
Чтобы добавить контакт в список введите: фамилию, имя и номер телефона через пробел
Эрик Темницкий 89157528504
Список контактов:
1. Эрик Темницкий: номер телефона - 89157528504. 

2
Чтобы добавить контакт в список введите: фамилию, имя и номер телефона через пробел
Доу  89157528506
Список контактов:
1. Эрик Темницкий: номер телефона - 89157528504. 
2. Доу: номер телефона - 89157528506. 

2
Чтобы добавить контакт в список введите: фамилию, имя и номер телефона через пробел
 Джейн 89157528508
Список контактов:
1. Эрик Темницкий: номер телефона - 89157528504. 
2. Доу: номер телефона - 89157528506. 
3. Джейн: номер телефона - 89157528508. 

3
Чтобы создать группу введите ее название
Друзья
Группа "Друзья" успешно добавлена в телефонную книгу "Мой список контактов".

4
Чтобы добавить контакт в группу введите название группы и номер контакта через пробел:
Список доступных групп:
1. Друзья.
Список контактов:
1. Эрик Темницкий: номер телефона - 89157528504. 
2. Доу: номер телефона - 89157528506. 
3. Джейн: номер телефона - 89157528508.
Друзья 1
Контакт Эрик Темницкий: номер телефона - 89157528504. успешно добавлен в группу "Друзья" телефонной книги "Мой список контактов"!

4
Чтобы добавить контакт в группу введите название группы и номер контакта через пробел:
Список доступных групп:
1. Друзья.
Список контактов:
1. Эрик Темницкий: номер телефона - 89157528504. 
2. Доу: номер телефона - 89157528506. 
3. Джейн: номер телефона - 89157528508. 
Друзья 3
Контакт Джейн: номер телефона - 89157528508. успешно добавлен в группу "Друзья" телефонной книги "Мой список контактов"!

4
Чтобы добавить контакт в группу введите название группы и номер контакта через пробел:
Список доступных групп:
1. Друзья.
Список контактов:
1. Эрик Темницкий: номер телефона - 89157528504. 
2. Доу: номер телефона - 89157528506. 
3. Джейн: номер телефона - 89157528508. 
коллеги 2
Группы "коллеги" не оказалось в телефонной книге "Мой список контактов", но Группа "коллеги" успешно добавлена в телефонную книгу "Мой список контактов".

5
Чтобы удалить контакт из группы введите название группы и номер контакта через пробел:
Список контактов:
1. Эрик Темницкий: номер телефона - 89157528504. 
2. Доу: номер телефона - 89157528506. 
3. Джейн: номер телефона - 89157528508. 
Список доступных групп:
1. Друзья
2. Коллеги
Друзья 1

6
Чтобы удалить группу контактов введние название группы:
Список доступных групп:
1. Друзья.
2. коллеги.
Друзья

7
Список контактов в группе "Друзья":
Эрик Темницкий: номер телефона - 89157528504.
*********************************************
Список контактов в группе "коллеги":
Доу: номер телефона - 89157528506.
Эрик Темницкий: номер телефона - 89157528504.
*********************************************

8
Чтобы получить список контактов в группе введите название группы:
Список доступных групп:
1. Друзья.
2. коллеги.
коллеги
Список контактов в группе "коллеги":
Доу: номер телефона - 89157528506.
Эрик Темницкий: номер телефона - 89157528504.

9
Введите номер телефона, чтобы найти контакт в телефонной книге:
89157528504
Контакт найден - Эрик Темницкий: номер телефона - 89157528504.

10
Введите имя и номер телефона, чтобы найти контакт в телефонной книге:
Джейн  89157528508
Контакт по имени и номеру телефона - Джейн 89157528508. не найден!

11
Введите фамилию и номер телефона, чтобы найти контакт в телефонной книге:
Доу 89157528506
Контакт найден - Доу: номер телефона - 89157528506.

12
Введите фамилию и имя, чтобы найти контакт в телефонной книге:
Эрик Темницкий
Контакт найден - Эрик Темницкий: номер телефона - 89157528504.
```

### **Моя реализация**:
1. Реализация осуществлена в парадигме ООП.
2. Создал структуру классов:

* **Program** - класс, отвечающий за запуск программы, путем инициирования метода *start()* с инициированием внутри себя
  вспомогательных ```void``` методов: 
  * *printMenu()* - выводит меню команд программы на экран;
  * *printContactsList()* - выводит список контактов на экран.  

#### Класс **Program**:
``` java
public class Program {
    private final List<Contact> contactsList = new ArrayList<>();
    private final Phonebook phonebook = new Phonebook("моя");
    private final Scanner scanner = new Scanner(System.in);

    public void start() {
        String input;
        String[] allInput;
        while (true) {
            try {
                printMenu();
                input = scanner.nextLine();
                if ("выход".equalsIgnoreCase(input) || "0".equals(input)) {
                    scanner.close();
                    break;
                } else {
                    var operationNumber = Integer.parseInt(input);
                    switch (operationNumber) {
                        case 1:
                            System.out.println(Utils.ANSI_BLUE + "Чтобы переименовать телефонную книгу введите " +
                                    "новое название" + Utils.ANSI_RESET);
                            input = scanner.nextLine();
                            phonebook.setPhonebookTittle(input);
                            break;
                        case 2:
                            System.out.println(Utils.ANSI_BLUE + "Чтобы добавить контакт в список введите: " +
                                    "фамилию, имя и номер телефона через пробел" + Utils.ANSI_RESET);
                            allInput = scanner.nextLine().split(" ");
                            contactsList.add(new Contact(allInput[0], allInput[1], allInput[2]));
                            printContactsList(contactsList);
                            break;
                        case 3:
                            System.out.println(Utils.ANSI_BLUE + "Чтобы создать группу введите ее название" +
                                    Utils.ANSI_RESET);
                            input = scanner.nextLine();
                            phonebook.createGroup(input);
                            break;
                        case 4:
                            System.out.println(Utils.ANSI_BLUE + "Чтобы добавить контакт в группу введите " +
                                    "название группы и номер контакта через пробел:" + Utils.ANSI_RESET);
                            phonebook.printGroupsList();
                            printContactsList(contactsList);
                            allInput = scanner.nextLine().split(" ", 2);
                            phonebook.addContactToGroup(allInput[0],
                                    contactsList.get(Integer.parseInt(allInput[1]) - 1));
                            break;
                        case 5:
                            System.out.println(Utils.ANSI_BLUE + "Чтобы удалить контакт из группы введите " +
                                    "название группы и номер контакта через пробел:" + Utils.ANSI_RESET);
                            phonebook.printGroupsList();
                            printContactsList(contactsList);
                            allInput = scanner.nextLine().split(" ");
                            phonebook.deleteContactFromPhoneBook(allInput[0],
                                    contactsList.get(Integer.parseInt(allInput[1]) - 1));
                            break;
                        case 6:
                            System.out.println(Utils.ANSI_BLUE + "Чтобы удалить группу контактов " +
                                    "введние название группы:" + Utils.ANSI_RESET);
                            phonebook.printGroupsList();
                            input = scanner.nextLine();
                            phonebook.deleteGroupFromPhoneBook(input);
                            break;
                        case 7:
                            phonebook.printPhoneBook();
                            break;
                        case 8:
                            System.out.println(Utils.ANSI_BLUE + "Чтобы получить список контактов в группе " +
                                    "введите название группы:" + Utils.ANSI_RESET);
                            phonebook.printGroupsList();
                            input = scanner.nextLine();
                            phonebook.contactsInGroupList(input);
                            break;
                        case 9:
                            System.out.println(Utils.ANSI_BLUE + "Введите номер телефона, " +
                                    "чтобы найти контакт в телефонной книге:" + Utils.ANSI_RESET);
                            input = scanner.nextLine();
                            phonebook.findContactByPhoneNumber(input);
                            break;
                        case 10:
                            System.out.println(Utils.ANSI_BLUE + "Введите имя и номер телефона, " +
                                    "чтобы найти контакт в телефонной книге:" + Utils.ANSI_RESET);
                            allInput = scanner.nextLine().split(" ", 2);
                            phonebook.findContactByNameAndPhone(allInput[0], allInput[1]);
                            break;
                        case 11:
                            System.out.println(Utils.ANSI_BLUE + "Введите фамилию и номер телефона, " +
                                    "чтобы найти контакт в телефонной книге:" + Utils.ANSI_RESET);
                            allInput = scanner.nextLine().split(" ", 2);
                            phonebook.findContactBySurnameAndPhone(allInput[0], allInput[1]);
                            break;
                        case 12:
                            System.out.println(Utils.ANSI_BLUE + "Введите фамилию и имя, " +
                                    "чтобы найти контакт в телефонной книге:" + Utils.ANSI_RESET);
                            allInput = scanner.nextLine().split(" ", 2);
                            phonebook.findContactBySurnameAndName(allInput[0], allInput[1]);
                            break;
                        default:
                            System.out.println(Utils.ANSI_RED + "Вы ввели неверный номер операции!" + Utils.ANSI_RESET);
                    }
                }
            } catch (NumberFormatException | IndexOutOfBoundsException e) {
                System.out.println(Utils.ANSI_RED + "Ошибка ввода!" + Utils.ANSI_RESET);
            }
        }
    }

    private static void printMenu() {
        System.out.println(Utils.ANSI_YELLOW + "Эта программа эмулирует работу телефонной книги!" + Utils.ANSI_RESET);
        System.out.println(Utils.ANSI_PURPLE + "Возможные команды программы:" + Utils.ANSI_RESET);
        System.out.println("0 или выход: выход из программы.");
        System.out.println("1: переименовать название телефонной книги.");
        System.out.println("2: добавить контакт в телефонную книгу.");
        System.out.println("3: добавить группу в телефонную книгу.");
        System.out.println("4: добавить контакт в группу.");
        System.out.println("5: удалить контакт из группы.");
        System.out.println("6: удалить группу вместе с контактами.");
        System.out.println("7: вывести телефонную книгу на экран.");
        System.out.println("8: вывести список контактов в заданной группе на экран.");
        System.out.println("9: найти контакт по номеру телефона.");
        System.out.println("10: найти контакт по имени и номеру телефона.");
        System.out.println("11: найти контакт по фамилии и номеру телефона.");
        System.out.println("12: найти контакт по фамилии и имени.");
    }

    private void printContactsList(List<Contact> contacts) {
        if (!contacts.isEmpty()) {
            System.out.println(Utils.ANSI_CYAN + "Список контактов:" + Utils.ANSI_RESET);
            for (var i = 0; i < contacts.size(); i++) {
                System.out.printf("%s%s. %s %s%n", Utils.ANSI_PURPLE, (i + 1), contacts.get(i), Utils.ANSI_RESET);
            }
        } else {
            System.out.println(Utils.ANSI_RED + "Список контактов пуст!" + Utils.ANSI_RESET);
        }
    }
}
```

* **Contact** - класс, описывающий контакта. имеет переопреденные *toString()*, *equals()* и *hashCode()*, а так же геттер-методы для доступа к полям: surname, name, phone;

#### Класс **Contact**:
``` java   
public class Contact {
    private String surname;
    private String name;
    private String phone;

    public Contact(String surname, String name, String phone) {
        this.surname = surname;
        this.name = name;
        this.phone = phone;
    }

    public String getPhone() {
        return phone;
    }

    public String getSurname() {
        return surname;
    }

    public String getName() {
        return name;
    }

    @Override
    public boolean equals(Object o) {
        if (o == this) {
            return true;
        }
        if (o == null || o.getClass() != this.getClass()) {
            return false;
        }
        var contact = (Contact) o;
        if (((surname == null) && (name == null)) || ("".equals(surname) && "".equals(name))) {
            return phone.equals(contact.phone);
        }
        if (surname == null || "".equals(surname) || surname.length() == 0) {
            return name.equals(contact.name) && phone.equals(contact.phone);
        } else if (name == null || "".equals(name) || name.length() == 0) {
            return surname.equals(contact.surname) && phone.equals(contact.phone);
        } else {
            return surname.equals(contact.surname) && name.equals(contact.name) && phone.equals(contact.phone);
        }
    }

    @Override
    public int hashCode() {
        return Objects.hash(surname, name, phone);
    }

    @Override
    public String toString() {
        if (((surname == null) && (name == null)) || ("".equals(surname) && "".equals(name))) {
            return "Неизвестный номер телефона - " + phone + ".";
        }
        if (surname == null || "".equals(surname) || surname.length() == 0) {
            return name + ": номер телефона - " + phone + ".";
        } else if (name == null || "".equals(name) || name.length() == 0) {
            return surname + ": номер телефона - " + phone + ".";
        } else {
            return surname + " " + name + ": номер телефона - " + phone + ".";
        }
    }
}
```

* **Phonebook** - класс, описывающий телефонную книгу. Методы описаны в ```JavaDoc```.

#### Класс **Phonebook**: 
``` java
public class Phonebook {
    private String phonebookTittle;
    private final Map<String, List<Contact>> phonebook = new HashMap<>();

    public Phonebook(String phonebookTittle) {
        this.phonebookTittle = phonebookTittle;
    }

    public void setPhonebookTittle(String phonebookTittle) {
        this.phonebookTittle = phonebookTittle;
    }

    public void createGroup(String tittle) {
        if (tittle != null || !"".equals(tittle)) {
            List<Contact> contactList = new ArrayList<>();
            phonebook.put(tittle, contactList);
            System.out.printf("%sГруппа \"%s\" успешно добавлена в телефонную книгу \"%s\".%s%n",
                    Utils.ANSI_GREEN, tittle, phonebookTittle, Utils.ANSI_RESET);
        } else {
            System.out.printf("%sПроизошла ошибка! Невозможно добавить группу \"%s\" в телефонную книгу \"%s\".%s%n",
                    Utils.ANSI_RED, tittle, phonebookTittle, Utils.ANSI_RESET);
        }
    }

    private boolean isContainsGroupTittleInPhonebookGroups(String tittle) {
        return phonebook.containsKey(tittle);
    }

    private boolean isContainsContactInGroup(String tittle, Contact contact) {
        return isContainsGroupTittleInPhonebookGroups(tittle) && phonebook.get(tittle).contains(contact);
    }

    public void printGroupsList() {
        if (!phonebook.isEmpty()) {
            var counter = 0;
            System.out.println(Utils.ANSI_PURPLE + "Список доступных групп:" + Utils.ANSI_RESET);
            for (String string : phonebook.keySet()) {
                counter++;
                System.out.printf("%s%s. %s.%s%n", Utils.ANSI_CYAN, counter, string, Utils.ANSI_RESET);
            }
        } else {
            System.out.println(Utils.ANSI_RED + "Список групп пуст!" + Utils.ANSI_RESET);
        }
    }

    public void addContactToGroup(String tittle, Contact contact) {
        if (isContainsGroupTittleInPhonebookGroups(tittle) && !isContainsContactInGroup(tittle, contact)) {
            phonebook.get(tittle).add(contact);
            System.out.printf("%sКонтакт %s успешно добавлен в группу \"%s\" телефонной книги \"%s\"!%s%n",
                    Utils.ANSI_CYAN, contact, tittle, phonebookTittle, Utils.ANSI_RESET);
        } else if (!isContainsGroupTittleInPhonebookGroups(tittle) && tittle != null && !"".equals(tittle) &&
                !isContainsContactInGroup(tittle, contact)) {
            System.out.printf("%sГруппы \"%s\" не оказалось в телефонной книге \"%s\", но %s",
                    Utils.ANSI_YELLOW, tittle, phonebookTittle, Utils.ANSI_RESET);
            createGroup(tittle);
            phonebook.get(tittle).add(contact);
        } else {
            System.out.printf("%sК сожалению, невозможно добавить %s в телефонную книгу \"%s\"!%s%n",
                    Utils.ANSI_RED, contact, phonebookTittle, Utils.ANSI_RESET);
        }
    }

    public void contactsInGroupList(String tittle) {
        if (phonebook.containsKey(tittle)) {
            List<Contact> contactsList = phonebook.get(tittle);
            if (!contactsList.isEmpty()) {
                System.out.printf("%sСписок контактов в группе \"%s\":%s%n",
                        Utils.ANSI_PURPLE, tittle, Utils.ANSI_RESET);
                for (Contact contact : contactsList) {
                    System.out.println(Utils.ANSI_CYAN + contact + Utils.ANSI_RESET);
                }
            } else {
                System.out.printf("%sГруппа \"%s\" пуста!%s%n", Utils.ANSI_RED, tittle, Utils.ANSI_RESET);
            }
        } else {
            System.out.printf("%sГруппа \"%s\" не найдена в телефонной книге \"%s\"!%s%n",
                    Utils.ANSI_RED, tittle, phonebookTittle, Utils.ANSI_RESET);
        }
    }

    public void printPhoneBook() {
        if (!phonebook.isEmpty()) {
            for (String string : phonebook.keySet()) {
                contactsInGroupList(string);
                Utils.printDelim();
            }
        } else {
            System.out.println(Utils.ANSI_RED + "Телефонная книга пуста!" + Utils.ANSI_RESET);
        }
    }

    public void deleteContactFromPhoneBook(String tittle, Contact contact) {
        if (!phonebook.isEmpty() && phonebook.containsKey(tittle)) {
            List<Contact> contacts = new ArrayList<>();
            contacts.add(contact);
            phonebook.remove(tittle, contacts);
        }
    }

    public void deleteGroupFromPhoneBook(String tittle) {
        if (!phonebook.isEmpty()) {
            phonebook.entrySet().removeIf(entry -> entry.getKey().equals(tittle));
        }
    }

    public void findContactByPhoneNumber(String phone) {
        for (List<Contact> contacts : phonebook.values()) {
            for (Contact contact : contacts) {
                if (contact.getPhone().equals(phone)) {
                    System.out.printf("%sКонтакт найден - %s%s%n", Utils.ANSI_GREEN, contact, Utils.ANSI_RESET);
                    return;
                }
            }
        }
        System.out.printf("%sКонтакт по номеру - %s. не найден!%s%n", Utils.ANSI_RED, phone, Utils.ANSI_RESET);
    }

    public void findContactByNameAndPhone(String name, String phone) {
        for (List<Contact> contacts : phonebook.values()) {
            for (Contact contact : contacts) {
                if (contact.getName() != null && contact.getName().equalsIgnoreCase(name) &&
                        contact.getPhone().equals(phone)) {
                    System.out.printf("%sКонтакт найден - %s%s%n", Utils.ANSI_GREEN, contact, Utils.ANSI_RESET);
                    return;
                }
            }
        }
        System.out.printf("%sКонтакт по имени и номеру телефона - %s %s. не найден!%s%n",
                Utils.ANSI_RED, name, phone, Utils.ANSI_RESET);
    }

    public void findContactBySurnameAndPhone(String surname, String phone) {
        for (List<Contact> contacts : phonebook.values()) {
            for (Contact contact : contacts) {
                if (contact.getSurname() != null && contact.getSurname().equalsIgnoreCase(surname) &&
                        contact.getPhone().equals(phone)) {
                    System.out.printf("%sКонтакт найден - %s%s%n", Utils.ANSI_GREEN, contact, Utils.ANSI_RESET);
                    return;
                }
            }
        }
        System.out.printf("%sКонтакт по фамилии и номеру телефона - %s %s. не найден!%s%n",
                Utils.ANSI_RED, surname, phone, Utils.ANSI_RESET);
    }

    public void findContactBySurnameAndName(String surname, String name) {
        for (List<Contact> contacts : phonebook.values()) {
            for (Contact contact : contacts) {
                if (contact.getSurname() != null && contact.getName() != null &&
                        contact.getSurname().equalsIgnoreCase(surname) && contact.getName().equalsIgnoreCase(name)) {
                    System.out.printf("%sКонтакт найден - %s%s%n", Utils.ANSI_GREEN, contact, Utils.ANSI_RESET);
                    return;
                }
            }
        }
        System.out.printf("%sКонтакт по фамилии и имени - %s %s. не найден!%s%n",
                Utils.ANSI_RED, surname, name, Utils.ANSI_RESET);
    }
}
```

2. Использовал кодирование цвета текста (ANSI).

#### Класс **Utils**:
``` java
public class Utils {
    public static final String ANSI_RESET = "\u001B[0m";
    public static final String ANSI_BLACK = "\u001B[30m";
    public static final String ANSI_RED = "\u001B[31m";
    public static final String ANSI_GREEN = "\u001B[32m";
    public static final String ANSI_YELLOW = "\u001B[33m";
    public static final String ANSI_BLUE = "\u001B[34m";
    public static final String ANSI_PURPLE = "\u001B[35m";
    public static final String ANSI_CYAN = "\u001B[36m";
    public static final String ANSI_WHITE = "\u001B[37m";

    public static void printDelim() {
        System.out.println(ANSI_GREEN + "*********************************************" + ANSI_RESET);
    }
}
```

3. Использовал ```try-catch```, чтобы избежать падение программы в исключения.

#### Метод *main()* в классе **Main**:
``` java
public class Main {
    public static void main(String[] args) {
        var program = new Program();
        program.start();
    }
}
```

## *Вывод в консоль*:

* меню:
``` 
Эта программа эмулирует работу телефонной книги!
Возможные команды программы:
0 или выход: выход из программы.
1: переименовать название телефонной книги.
2: добавить контакт в телефонную книгу.
3: добавить группу в телефонную книгу.
4: добавить контакт в группу.
5: удалить контакт из группы.
6: удалить группу вместе с контактами.
7: вывести телефонную книгу на экран.
8: вывести список контактов в заданной группе на экран.
9: найти контакт по номеру телефона.
10: найти контакт по имени и номеру телефона.
11: найти контакт по фамилии и номеру телефона.
12: найти контакт по фамилии и имени.
```