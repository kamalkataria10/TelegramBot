Excitement fills me as I introduce my latest project—the Telegram Weather Update Bot. This cutting-edge bot revolutionizes the way users stay informed about weather conditions, offering a user-friendly experience with just two key commands.

The initial command, "/subscribe [cityname]," empowers users to receive daily weather updates. At 9:00 AM, a scheduled task, facilitated by the node-cron package, fetches active subscriptions from the database. The bot then dispatches personalized weather updates to individual chatIds based on their chosen city, seamlessly executed through the node-telegram-bot-api.

The second command, "/weather [cityname]," grants users instant access to weather details for any city, eliminating the need for a subscription.

Locate the Telegram Bot Handle at t.me/WeatherUpdateASTBot.

To elevate user interaction, I've crafted an admin panel with robust features for managing user accounts, including deletion and subscription blocking. Furthermore, I've integrated a bot settings section, allowing users to effortlessly update their API keys. To streamline these functionalities, I've established a REST API that retrieves data from a MongoDB database storing information such as subscribed users and bot settings. The UI for the admin portal is developed using react.js.

Facilitating seamless communication between the Telegram bot and my backend, I've harnessed the power of the node-telegram-bot-api library, leveraging the supplied API key.

## Tech Stack

**Client:** React.js, Telegram Bot

**Backend** MongoDb, Express and Node.js
