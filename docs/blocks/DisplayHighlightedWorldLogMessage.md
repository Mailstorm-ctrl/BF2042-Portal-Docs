# DisplayHighlightedWorldLogMessage

Displays a **Message** on the world log for 6 seconds. If no target is provided, it will display the **Message** to everyone.  
  
_Note: This will only appear to players that are deployed on the map. It\'s your responsibility to ensure a safe and fair experience for others, violating the EA User Agreement by using offensive or inappropriate text may result in account bans._

### Inputs

1. Message
2. Player | TeamId

    _Optional_

```blockly
<block type="ShowHighlightedGameModeMessage">
    <value name="VALUE-0">
        <block type="Message">
            <value name="VALUE-0">
                <block type="Text">
                    <field name="TEXT">Hello World!</field>
                </block>
            </value>
        </block>
    </value>
    <value name="VALUE-1">
        <block type="EventTeam"></block>
    </value>
</block>
```
