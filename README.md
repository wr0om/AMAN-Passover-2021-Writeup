# AMAN Challenge Writeup
www.idf.il/אתרים/אגף-המודיעין/2021/חידת-מודיעין-אמן-פסח-אתגר-צהל-חידה/

We start the challenge by getting a translation of the popular song Dayenu (דיינו) from hebrew to english.
As we read it, we can notice spelling mistakes throughout the song.

For example, "sufficed" (the #1 spelling mistake) becomes "sufliced" in the song - and so forth.
let's list all the mistakes by order:
1. sufficed – sufliced
2. had - hed
3. sea - tea
4. ...

We can notice that all of the spelling mistakes are mistakes of 1 letter that is misplaced - 'l' instead of an 'f' for sufficed.
let's make a string using these mistakes, we start with the letter 'l'.
As we see, we get the string "letmypeoplego".

At the bottom of the page, below the song, we see - "Who said ____________?"

We place the word we found - **Who said let my people go? - Moses**.

We get a link - _www.idf.il/_____/י/_.
We place "Moses" inside the link (in hebrew like stated below - "משה"),
and continue to the next stage located at **www.idf.il/משה/י/**.

We get this sentence:
"יש מי שחושב שסיפור יציאת מצרים הוא פנטזיה, אך תוך כדי ויכוח טוב, תוכלו להראות את העובדה הבאה ולהוכיח, שאין זו..."
And string: "בט.טזחובד, גא.____טו"

"אין זו אגדה" - is a known saying referenced in the first sentence given (phrase from "Altneuland" - book by Theodor Herzl).

We place the word "אגדה" in the given string: **"בט.טזחובד, גא.אגדהטו"**.
Underneath the string there is another hint: "בסמוך תמצאו עיר שמסמלת ניצחון כואב" - near you will find a city that symbolizes a painful victory.
From the format of the given string and that hint, we can assume the string is coordinates.

By using Gematria (where each character is equal to a number), we get these coordinates: **29.978624, 31.134596**.
which leads us to The Great Pyramid of Giza.

![image](https://user-images.githubusercontent.com/59180254/112946982-df94c180-913e-11eb-861d-bde497257d19.png)

Close to the pyramid, we can spot a city called "6th of October".
This city's name commemorates the commencement of the 1973 Arab–Israeli War on 6 October 1973 - which was a painful victory for Israel (the hint from earlier checks out).

![image](https://user-images.githubusercontent.com/59180254/112949244-ae69c080-9141-11eb-8b5f-86b7b2afc56a.png)

So that's it? we finished the challenge? not yet.
We still haven't found a way to send the answer to AMAN.

By searching around on the site, I stumbled upon this image with morse code shown at the bottom of it.

![image](https://user-images.githubusercontent.com/59180254/112947546-9729d380-913f-11eb-960b-060f04d01154.png)

**.... .. -.. .- .-.-.- .. -.. ..-. .-.-.- .- -- .- -. .--.-. --. -- .- .. .-.. .-.-.- -.-. --- --**

The morse code translates to: **"HIDA.IDF.AMAN@GMAIL.COM"**

That's it, now all we have to do is send the answer (The Great Pyramid of Giza) to this email adress.
