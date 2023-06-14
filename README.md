# email
-------------------------------------------------------------------------------------------
Provide email service for demo app in order to send activation email for registered users.
-------------------------------------------------------------------------------------------
The email service behaves as a Kafka consumer and listens to Kafka topic 'activation-email'.
If requested, it will deserialize the request and invoke service to send activation email containing 
preset html template providing url for account activation to registered email.
