# MADPractical11_20012021026
Create two Activities like MainActivity, NoteViewActivity according to below UI design.

Use RecyclerView Code from Practical-9 to display Note Data.

Use Broadcast Receiver, Time Picker Dialog, service & AlarmManager code from Practical-7

Create Note class with member variables like id, title, subTitle, Description, modifiedTime, reminderTime:Long, isReminderEnable:Boolean & create membor methods like getCurrentDateTime(), getMillis(), setReminder(), isValid(), getReminderText(), saveNote(), getHour(), getMinute(), calculateReminder() 

Create DatabaseHelper Class for SQlite with member methods like insertNote(), getNote(id), getAllNotes(), getNotesCount(), updateNote(), deleteNote().

Use Databinding in gradle file to easy way integrate xml into kotlin file

Use Material 3 design for UI

create class NotesData with companion object and it will store column name of table and create table query.

Create NoteViewActivity. It will show while reminder notification is turned up and user click on notification. It will also show when click on Note in recyclerView. After clicking on notification NoteViewActivity should be open with full description of that note. 

Note should be deleted by clicking on icon of Delete. Note should not be added if any one field of note is empty.

Some notes have reminder time so add reminder time in alarmManager with note id & it should be receive in broadcast receiver & in broadcast receiver notification should be generated with title & description of note.

If More than one notes have reminder time then notification should be displayed for each note separately.

Create Common Custom Dialog Box for add, edit note.

Create RecyclerView & its adapter to display all notes.

![Screenshot 2022-11-16 184719](https://user-images.githubusercontent.com/79136705/202199562-3da2d809-a912-4f9c-86cf-069258a5dffa.png)
![Screenshot 2022-11-16 184736](https://user-images.githubusercontent.com/79136705/202199572-0d11412a-ac54-452c-bfb5-e60a65337bf0.png)
![Screenshot 2022-11-16 184835](https://user-images.githubusercontent.com/79136705/202199578-652a5d38-800a-49d3-a489-154fe21e9da4.png)
![Screenshot 2022-11-16 185425](https://user-images.githubusercontent.com/79136705/202199586-b68247c4-3199-4ac4-acee-4f2ddb1cba0c.png)
![Screenshot 2022-11-16 185757](https://user-images.githubusercontent.com/79136705/202199592-7d48b30e-b2af-4e62-b5e5-392b2cf80cb2.png)
![Screenshot 2022-11-16 185850](https://user-images.githubusercontent.com/79136705/202199598-11375473-0eb5-4217-8a7a-32794d70387c.png)
![Screenshot 2022-11-16 190023](https://user-images.githubusercontent.com/79136705/202199604-f8495f58-ca5a-4dfb-9cb0-c85d65f4f4ec.png)





