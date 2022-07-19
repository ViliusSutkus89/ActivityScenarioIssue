# ActivityScenarioIssue

Repository to demonstrate issue https://github.com/android/android-test/issues/1433

# Workaround

Workaround is ActivityTestRule for pre Lollipop, ActivityScenario for Lollipop and later.

Implemented in [workaround](https://github.com/ViliusSutkus89/ActivityScenarioIssue/tree/workaround) branch.

https://github.com/ViliusSutkus89/ActivityScenarioIssue/blob/workaround/app/src/androidTest/java/com/viliussutkus89/activityscenarioissue/ExampleInstrumentedTest.kt

Probably does not cover all cases, but works for me.
