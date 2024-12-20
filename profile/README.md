## Better Pronto

----

#### What is Better Pronto?
Better Pronto aims to create a fast, secure, and lightweight Python client for Stanford Online High School's official chat platform, Pronto. In the Fall of 2023, the Stanford OHS administration team made the decision to create an official chat platform for their students and staff, following a widespread incident the previous academic year in which many unofficial Skype chats (which were a main and unofficial method of communication among students at the time) were hacked and spammed by a group of students who had discovered a bug in the platform.

While Pronto is a relatively secure platform compared to the previous alternatives of Skype and Discord (secure in the only sense that only registered OHS students and staff can join the platform), the official web and desktop clients are bloated (taking over 300 MB of memory), laggy, and generally very unpleasant to use. Many students have complained that while the security of the platform is an improvement, the UI customization is sparse and minimal, many key features are missing from the application, and the application is exceedingly slow, such that Pronto as a whole is unpreferable to less "secure" alternatives. Furthermore, in recent months, concern has been raised regarding the privacy of students both in direct messages as well as in public group chats. The Pronto and Stanford OHS administration teams have confirmed on multiple occasions that they are able to see all group and individual messages on the platform and have been known to take action upon these messages in the past, with such action often being criticized as invasive and ignorant of context. These three factors of privacy, customizability, and speed have led to less than a fifth of the entire school even so much as checking their accounts in the last month, and almost a third never even activating their accounts, even though the platform is estimated to cost the school around 50k USD/year and has been integrated directly into Canvas.

#### The Mission
Better Pronto aims to solve these three problems in the following manner:

- Security: Creating a client-to-client encryption system, such that anyone not given direct authorization (in the form of an encryption key) to view decrypted messages by the group chat owner will only see a mess of encrypted gibberish.
- Customizability: Creating a feature-rich environment, adding more options for reactions, allowing users to find group chats and direct messages faster, and allowing for maximal UI and client customizability while still maintaining stellar performance.
- Speed: Creating a lightweight, transparent, and easy-to-use Python wrapper for the official Pronto API, allowing for fast and concentrated development of the client, as well as encouraging the vibrant Stanford OHS community to meaningfully contribute to the project.
