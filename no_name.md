---
id: 9caa1a8d-17a0-4616-a262-5e2fde9925c1

---
#


Add this logic to pc app:
Pc app also has no_name.md always shown in list. (Now it is only shown if any data is present) It is also highlighted like now. 
When clicked to open - instantly enters edit mode one line below hashtag with empty header.

If user changes a header - this creates an entirely newn note with name that has in the header and UUID the same way if user was to press "new note" button.
Recheck if this is applien in phone app - may be absent or incomplete there.

When any data entered in no_name even without saving - this data gets synched per time set in settings or  3 minites after no changes were added, whichever comes first. This 3 min timer only runs ones per any content entry excluding spaces or tabs in no_name.md note.

If while synching comes data from another device to same no_name new data is added per timestamp. This means new logic for both phone apl and pc app:

For any note not only content is synched (in any synch logic) but also time when it was entered.
Thus way of synch nut only oushesh update but also pulls them for same note - their content wont getblost, bit wi egt merged based on timeline.

Based on that time, if new data that comes from another device after synching for same note was entered before data on pc was added - then ot goes with one empty line gap above text that was added latest on pc.
If it is older - then it goes on the bottom of the note leaving one line gap.


Adpot for pc app same logic that is already set in phone app: after saving any note (exiting edit mode) engage synch automatically.





---

https://www.aliexpress.com/item/1005008431409591.html?browser_id=45a5d03eadcb467c87b224f7fa3177a9&aff_platform=msite&m_page_id=ofw0i7jsmrkcavkd1a0e27c211b4646c9644f5f01e&gclid=&pdp_ext_f=%7B%22order%22%3A%2219134%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%211.26%211.26%21%21%219.39%219.39%21%400b0fe08917905061808514710e0e18%2112000045067677014%21sea%21EE%21192939342%21X%211%210%21n_tag%3A-29919%3Bd%3A10543600%3Bm03_new_user%3A-29895&algo_pvid=515fcfe4-c86b-4837-ab21-2a6498ee2402&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008431409591%7C_p_origin_prod%3A

---
