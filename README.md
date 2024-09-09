# 03-Kotlin
A small frontend bot written in Kotlin that communicates with Discord. You can ask it for all items in the shop, categories of items in the shop and items in the given category, using keywords "items", "categories" and "in" respectively. The bot is not approved in Discord and thus can only see the messages directed specifically to it, so pleas use `@ShopBot` in the Discord chat.

If you want to host the bot you need copy the secret key from the `suspicious` file in the main folder, turn it with Ceasar Cypher with a step 13 (for example, here: https://cryptii.com/pipes/caesar-cipher) and copy the file to the `./app/.env` path.

To run the application run the gradle script in the main directory:

`./gradlew run`

Link to the chat: https://discord.gg/U9ZscjGn

