When you create a rule, first give it a clear name and description. You must indicate when it triggers and if further rules in the group must not be executed.

Each trigger is pretty self-explanatory. Firefly does not support regular expressions or other fancy things. If you set the checkbox "stop processing" and the trigger is hit, the triggers below will NOT be checked.

Firefly does not support rules that check for "A OR B". For example, you cannot do this: _Fire this rule when the description is either 'purple' OR 'red'.

However, you can add many checks, and check the "stop processing"-checkbox for all of them. Then, when the first one hits, the rest are skipped. This is almost, but not entirely the "OR"-check. If this seems too complicated, skip it for now.

Each action seems pretty obvious. Remember that you cannot set a budget on anything but a withdrawal, so creating such a action will not influence transfers. It's also impossible to change the source or destination account on a split transaction.

If you are unhappy about the order of the triggers or actions, please see the main page. There you can drag-and-drop them into the correct order.