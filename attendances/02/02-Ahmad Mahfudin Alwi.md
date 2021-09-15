#### Resume material week 2 by Ahmad Mahfudin Awi

# Activities and Intent

## Activities

An Activity is an application component represents one window, one hierarchy of views. Typically fills the screen, but can be embedded in other activity or a appear as floating window java class, typically one activity in one file.

In activities Represents an activity, such as ordering groceries, sending email, or getting directions. Activities handle user interactions and so much other proccess.

### Step to implement activities

<ol>

<li>Define layout in XML</li>
<li>Define Activity Java class</li>
<li>Connect Activity with Layout</li>
<li>Declare Activity in the Android manifest</li>

</ol>

## Intent

An intent is a description of an operation to be performed. An Intent is an object used to request an action from another app component via the Android system.

In intent can be used for Start activities, Start services, and Deliver broadcasts.

### Explicit and implicit intents

#### Explicit intents

Starts a specific activity (Request tea with milk delivered by Nikita -> Main activity starts the ViewShoppingCart activity)

#### Implicit intents

Asks system to find an activity that can handle this request (Find an open store that sells green tea -> Clicking Share opens a chooser with a list of apps)
