
  ![Acsify logo](https://acsify.com/acsify_logo_wit.png#gh-dark-mode-only)
  ![Acsify logo](https://acsify.com/acsify_logo_zwart.png#gh-light-mode-only)

# ACSIFY.COM

ACSIFY helps organizers with NFC wristbands that serve as multifunctional tools for event management. These wristbands streamline ticketing, enhance security, offer cashless payment options, provide access control, and enable various event-specific services, ultimately improving the overall attendee experience while offering valuable insights to event organizers.

# Discliamer
#### At this stage, this system is developed for a school project and is not yet ready for real-world use. I aspire to refine it and eventually launch it as a product, with the hope of providing practical solutions in the future.
# Features

- **Ticketing Solution**: ACSIFY's NFC wristbands serve as a convenient and secure alternative to traditional paper tickets. Attendees can simply tap their wristbands to gain access to the event, reducing the risk of counterfeit tickets.

- **Payment System**: These wristbands also function as cashless payment systems. Attendees can load funds onto their wristbands and use them to make purchases at event vendors, reducing the need for cash and enhancing convenience.

- **Access Control**: Event organizers can use NFC wristbands to control access to specific areas within the event venue. This helps maintain security and ensures that only authorized individuals can enter restricted zones.

- **Identification**: Each wristband is unique, enabling efficient attendee identification. This feature is particularly useful for events with age restrictions, VIP sections, or other special access requirements.

- **Enhanced Services**: ACSIFY's NFC wristbands can be programmed to offer enhanced services, such as fast-track entry, VIP privileges, or special discounts. This customization allows event organizers to tailor the attendee experience.

- **Data Insight**s: The technology behind these wristbands allows event organizers to collect valuable data on attendee behavior and preferences. This data can be used to improve future events and marketing strategies.


## Tech Stack

**NFC-tag:** NTAG215

**Client:** Dart, Flutter, Svelte

**Server:** Node, Express

**Storage:** Postgres, Prisma

## Media
This section contains media of the working system and or diagrams and flows of the system

![App Screenshot](https://raw.githubusercontent.com/Th1b0/th1b0.github.io/main/GIP.png)


## FAQ

#### How does it work?

Organizations can access a special section of my application, connected to a central server and a secure database, along with empty NFC tags. Using authorized devices, employees can set up these NFC tags with important personal user information such as their name, first name, phone number, email address, and address, along with a PIN code. This information is then sent to a central server, which responds by writing a unique, encrypted identifier (Universally Unique Identifier or UUID) to the NFC tag.

Permissions for this process are managed by the scanners that run the app. Additionally, once the configuration of the empty tag is complete, users can conveniently scan the QR code on their wristband to add money to it.

#### Is it safe?

Yes, it is safe. We've implemented several security measures to ensure the protection of your data:

- **Password Protection:** Each NFC tag can only be read or rewritten with a unique password, which is automatically changed after each scan and securely stored in our database.

- **Dynamic UUID:** The UUID on the NFC tag changes after each scan, making it extremely difficult for anyone to intercept or replicate your data.

- **Unique UID Encryption:** We encrypt the UUID on the NFC tag using the tag's Unique Identifier (UID), making each tag uniquely secure and impossible to copy.

- **PIN Requirements:** Extra security is ensured by requiring a PIN code for consecutive scans within a very short period or for transactions above a certain value.

- **End-to-End Encryption:** All data transmitted between the NFC tag, the app, and the central server is fully encrypted, ensuring maximum privacy and security.

- **Real-time Fraud Detection:** Our system continuously monitors transactions for suspicious activities and can take immediate action if potential fraud is detected.

These security features work together to provide a safe and reliable experience for our users.


## Used By

This project is used by the following companies:

- thibokuijpers.be
- acsify.com



## Feedback

If you have any feedback, please reach out to our feedback mail feedback@acsify.com


## Support

For support, support@acsify.com


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Author

[@Th1b0](https://www.github.com/Th1b0)

