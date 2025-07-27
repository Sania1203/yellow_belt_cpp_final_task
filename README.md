This is my final project for C++ yellow belt - Database for pairs date - event.

Commands:
Add <date> <event>;
Print;
Find <condition>;
Del <condition>;
Last <date> — cout the least event happened before date.

Condition types:
Find date < 2017-11-06 — find all events that happened before 2017-11-06;
Del event != "holiday" — deleting all the events except «holiday»;
Find date >= 2017-01-01 AND date < 2017-07-01 AND event == "sport event" — find all «sport event», happened in the first half of 2017;
Del date < 2017-01-01 AND (event == "holiday" OR event == "sport event") — delete all the «holiday» and «sport event», happened before 2017.
