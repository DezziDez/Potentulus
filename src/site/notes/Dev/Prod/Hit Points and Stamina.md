---
{"dg-publish":true,"permalink":"/dev/prod/hit-points-and-stamina/"}
---

# Hit Points
Every character has hit points. These hit points determine how much punishment anyone can take at any one time.

The maximum number of hit points a character has is calculated by adding their rank in Vitality twice and then adding their rank in Will twice. 

For example, if you have 3 ranks in Vitality and 2 ranks in Will, you would add Vitality twice, 3+3 = 6. Then add your Will twice, 2+2 = 4. Then add those together, 6+4 = 10. In this example, you would have 10 hit points.

# Stamina
Every character has stamina. This is the fuel for action and represents the amount of evergy a character has.

The maximum number of stamina a character has is calculated by adding their rank in Vitality twice and then adding their rank in Agility twice. The primary difference between stamina and hit points is how they are used and regained.

Whenever a character uses an [[Dev/Prod/Basic Actions\|action]] they consume stamina. A basic action uses 1 stamina and some skill actions cost more stamina to be used. Additionally, using more actions costs more stamina by adding the cost of the previous action to the cost of the action they are taking.

For example, your first basic action would cost 1 stamina, your second basic action would cost 1 stamina for your previous action and 1 stamina for the action, making it cost 2. Your 3rd basic action would cost 2 stamina for your previous action and 1 stamina for the action making the total cost 3. After 3 basic actions are spent you would have spent a total of 1+2+3=6 stamina.

Stamina is reset back to its maximum at the beginning of the character's turn and actions taken on the previous turn no longer effect that cost of actions made on the new turn.

### Continuous Costs
Some actions have reoccurring or continuous stamina costs. That means there is some cost at the beginning of a characters turn they must pay to continue an action that has some constant benefit. Continuous costs do not appear on basic actions. A continuous costs does count as an action and its cost must be added to your next action.

A continuous costs will be referenced in the skill or item effect and will be marked with a "C" in action cost.

### Quick Actions
There are some points where an action needs to be made extremely quickly and outside of the characters turn. This is known as a quick action. Quick actions cost twice as much as using a regular action on a characters turn and must also include the cost of the last action that character made.

Any action may be used as a quick action and it is encouraged for characters to be creative with how and when they spend their stamina.