# sample-template-betterdiscord
A sample template for Better Discord javascript plugins!
/**
 * @name MyPlugin
 * @version 1.0.0
 * @description A sample BetterDiscord plugin
 * @author AuthorName
 */

module.exports = class MyPlugin {
    constructor() {
        this._config = {
            info: {
                name: "MyPlugin",
                version: "1.0.0",
                description: "A sample BetterDiscord plugin",
                author: "AuthorName"
            }
        };
    }

    start() {
        console.log("MyPlugin started!");
    }

    stop() {
        console.log("MyPlugin stopped!");
    }
};

