# anywhere-1-click
*firefox exetention for netfree anywhere 2 users*

**click [here](https://github.com/chaim-chv/anywhere-1-click/raw/master/anywhere_1_click-1.0.1-fx.xpi) to download the add-on**

I created this add-on for myself, and i posting it here, it may be people can enjoy it.


__description:__

Whenever netfree anywhere 2 log out, for whatever reason, you need to log into the software settings page and click "Save and Reconnect", wait for login / connection failure and click again. This process is long - and also grabs another tab in the browser, which is particularly troublesome for me (laptop).
There is a solution to avoid logging in to the settings page, which is by bookmarking a javascript command with fetch to the anywhere reconnecting page. The problem in this way is that you do not see any message if the process was successful or failed, you just have to guess.

This addon - by clicking on the browser plugin icon connects to the anywhere connection page, and at the end of the process also returns the software response - in case of successful connection the message will be "success" and in case of failure - "error" - with detail. In case of an error, simply click the extension again and it will repeat the process.

Clicking on the plugin will create a connection request for the form of connection you already have in anywhere. To change the form of the connection, you will need to log in to the standard anywhere settings page.

Note: Instead of clicking the extension icon every time, you can set a combination with a plugin shortcut. In Firefox, press ctrl+shift+A to sign in to the Extensions Manager, click the Settings icon, then click on add-on shortcut management, and configure your shortcut to the add-on (in default is configured on Alt+Shift+Y).
