# Roles Bot Translations

Community translations of the [Discord Roles Bot](https://roles.bot)

## How to contribute
**We appreciate your help!** If your Pull Request gets merged, you can contact us on our [Support Server](https://discord.gg/8VZ69XyJeQ) to receive a **Translator role**. Alternatively, you can include your Discord username in the commit message.

**Command descriptions need to below 100 characters in length!**

### Adding a new language
1. Clone / Fork the repository
2. Create a new file for the desired language (e.g. `fr.json` for French)
   - Name should follow [Discord's supported languages and acronyms](https://discord-api-types.dev/api/discord-api-types-rest/common/enum/Locale#Enumeration%20Members)
3. You can copy the contents of `_.empty.json` in your new file
   - Make sure you follow the schema in `_.schema.json`
4. Translate the properties from `en_us.json` (or any other complete translation)
   - Feature names like "Auto Roles" should not be translated.
   - If your translation does not cover everything, please don't leave empty JSON strings (`""`). Instead, don't include the missing properties in your file. The bot will use English as a fallback language.
5. Create a Pull Request! 🎉

### Completing an existing language
1. Clone / Fork the repository
2. Add the missing properties to an incomplete file
   - Make sure you follow the schema in `_.schema.json`
3. Create a Pull Request! 🎉
