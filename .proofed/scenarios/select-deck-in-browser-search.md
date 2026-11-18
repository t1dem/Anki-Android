---
name: Apply a deck filter from card browser search
target: android
execution: local
device: Pixel_8_API_34
os_version: '14'
timeout_minutes: 10
paths: [AnkiDroid/src/main/java/com/ichi2/anki/CardBrowser.kt, AnkiDroid/src/main/java/com/ichi2/anki/CardTemplateEditor.kt, AnkiDroid/src/main/java/com/ichi2/anki/DeckSpinnerSelection.kt, AnkiDroid/src/main/java/com/ichi2/anki/NoteEditorFragment.kt, AnkiDroid/src/main/java/com/ichi2/anki/browser/CardBrowserFragment.kt, AnkiDroid/src/main/java/com/ichi2/anki/browser/search/StandardSearchFragment.kt, AnkiDroid/src/main/java/com/ichi2/anki/dialogs/DeckSelectionDialog.kt, AnkiDroid/src/main/java/com/ichi2/anki/instantnoteeditor/InstantNoteEditorActivity.kt, AnkiDroid/src/main/java/com/ichi2/anki/pages/ImageOcclusion.kt, AnkiDroid/src/main/java/com/ichi2/anki/pages/Statistics.kt, AnkiDroid/src/main/java/com/ichi2/anki/reviewreminders/ScheduleReminders.kt, AnkiDroid/src/main/java/com/ichi2/anki/utils/ext/BundleUtils.kt, AnkiDroid/src/main/java/com/ichi2/widget/cardanalysis/CardAnalysisWidgetConfig.kt, AnkiDroid/src/main/java/com/ichi2/widget/deckpicker/DeckPickerWidgetConfig.kt, AnkiDroid/src/main/res/layout/dialog_deck_picker.xml, AnkiDroid/src/main/res/menu/deck_picker_dialog_menu.xml, AnkiDroid/src/test/java/com/ichi2/anki/dialogs/DeckSelectionDialogTest.kt]
---
1. If the welcome screen is open, tap **Get Started** to open the deck list.
2. Tap the top-left menu button and choose **Settings**. Scroll to the bottom of the Settings list and tap **Developer options**, between **Advanced** and **About**.
3. Scroll down within **Developer options** to **Work in progress**. Tap **New card browser search view** so its switch is on. Use the top-left back arrows to return to the deck list.
4. Open the top-left menu and tap **Card browser**. Tap the search field at the top. Wait for the leftmost chip below the search field, just before **Flags**, to show the current deck name.
5. Tap that chip. In **Deck search**, tap **All decks**.
6. After the picker closes, check that the leftmost chip below the search field reads **All decks**.

Stop after this check.
