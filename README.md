# Order Processing System for Yandex Market and Ozon

## Overview

This project is designed to streamline the processing of orders from Yandex Market and Ozon, two of the largest e-commerce platforms in Russia. The system retrieves order data from these platforms, processes the information, and sends order details to a specified Telegram channel for further action or notification.

## Features

- **Order Retrieval**: Automatically fetch orders from Yandex Market and Ozon.
- **Data Processing**: Parse and process order details including customer information, product details, and order status.
- **Notification System**: Send order details to a designated Telegram channel.


## Configuration

1. **Telegram Bot Setup**:
   - Create a new bot via [BotFather](https://core.telegram.org/bots#6-botfather).
   - Obtain the API token for your bot.

2. **API Credentials**:
   - Obtain API keys and access credentials from Yandex Market and Ozon.

3. **Environment Variables**:
   - Set up the following environment variables with your credentials:

```bash
export TELEGRAM_TOKEN="your_telegram_bot_token"
export TELEGRAM_CHAT_ID="your_telegram_chat_id"
export YANDEX_API_KEY="your_yandex_market_api_key"
export OZON_API_KEY="your_ozon_api_key"
```


### Example Workflow

1. **Fetch Orders**:
   - Orders are fetched from Yandex Market and Ozon using API requests.

2. **Process Orders**:
   - Extract relevant information such as order ID, customer name, product details, and order status.

3. **Send to Telegram**:
   - Format the order details into a readable message.
   - Send the message to the specified Telegram channel.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the Apache License 2.0. See the License file for details.

## Contact

For any questions or support, please contact [barashtech@gmail.com](mailto:barashtech@gmail.com).

