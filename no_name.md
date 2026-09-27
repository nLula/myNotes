---
id: 9caa1a8d-17a0-4616-a262-5e2fde9925c1

---
#


Add this logic to pc app:
Pc app also has no_name.md always shown in list. (Now it is only shown if any data is present) It is also highlighted like now. 
When clicked to open - instantly enters edit mode one line below hashtag with empty header.

If user changes a hesder - this creates an entirely newnnote with name that was in the header and UUID the same way if user was to prass "new note" button.

When any data entered in no_name even without saving - this data gets synched per time set in settings or  3 minites after no changes were added, whichever comes first. This 3 min timer only runs ones per any content entry excluding spaces or tabs in no_name.md note.

If while synching comes data from another device to same no_name new data is added per timestamp. This means new logic for both phone apl and pc app:

For any note not only content is synched (in any synch logic) but also time when it was entered.
Based on that time, if new data that comes from another device after synching was entered before data on pc was added - then ot goes with one empty line gap above text that was added latest on pc.
If it is older - then it goes on the bottom of the note leaving one line gap.

