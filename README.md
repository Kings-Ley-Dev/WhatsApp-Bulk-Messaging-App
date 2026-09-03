# Welcome to the WhatsApp Business Bulk Messaging Project

The WhatsApp Business Bulk Messaging app is a Django-based application designed to send personalized WhatsApp messages to multiple contacts at once. It integrates with the Twilio API to leverage WhatsApp’s messaging service, making it ideal for businesses needing to communicate with customers, share promotions, or send updates in bulk.

## Key Features:
- Bulk Messaging: Users can send messages to all contacts in their database or upload new contact lists via CSV. 
- Customizable Messages: Each message can be personalized for each contact.
- Async Message Sending: Utilizes Celery and Redis to handle large message volumes asynchronously, ensuring efficient performance.
- Admin Interface: Django’s admin interface allows easy management of contacts, messages, and settings.

This setup provides an efficient, scalable way to manage WhatsApp communication, particularly for small businesses and marketing purposes.