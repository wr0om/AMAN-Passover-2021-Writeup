# HIDA_AMAN Writeup

We start the challenge by getting a translation of the popular song Dayenu (דיינו) from hebrew to english.
As we read it, we can notice spelling mistakes throughout the song.

for example, "sufficed" (the #1 spelling mistake) becomes "sufliced" in the song - and so forth.
lets list all the mistakes by order:
1. sufficed – sufliced
2. had - hed
3. sea - tea
4. ...

We can notice that all the spelling mistakes are mistakes of 1 letter out of place - 'l' instead of an 'f' for sufficed.
let's make a string using those mistakes, we start with the letter 'l'.
As we see, we get the string "letmypeoplego".

At the bottom of the page, below the song, we see - Who said ____________?
We place the word we found - **Who said let my people go? - Moses**.

We get a link - _www.idf.il/_____/י/_.
We place "Moses" inside the link (in hebrew like stated below - "משה"),
and continue to the next stage located at www.idf.il/משה/י/.

We get this sentence:
"יש מי שחושב שסיפור יציאת מצרים הוא פנטזיה, אך תוך כדי ויכוח טוב, תוכלו להראות את העובדה הבאה ולהוכיח, שאין זו..."
And string: "בט.טזחובד, גא.____טו"

"אין זו אגדה" - is a known saying referenced in the first sentence given (phrase from "Altneuland" - book by Theodor Herzl).

We place the word "אגדה" in the given string: "בט.טזחובד, גא.אגדהטו".
Underneath the string there is another hint: "בסמוך תמצאו עיר שמסמלת ניצחון כואב" - near you will find a city the symbolizes a painful victory.
From the format of the given string and that hint, we can assume the string is coordinates by using Gematria (where each character is equal to a number).
we get these coordinates: **29.978624, 31.134596** which lead us to The Great Piramid of Giza
![image](https://user-images.githubusercontent.com/59180254/112946982-df94c180-913e-11eb-861d-bde497257d19.png)

Near the piramid, we can see a city called "6th of October".
This city's name commemorates the commencement of the 1973 Arab–Israeli War on 6 October 1973 - which was a painful victory for Israel (the hint from earlier checks out)

So that's it? we found the answer right? no.
We still haven't found a way to send the answer to AMAN.

By searching around on the site, I stumbled on this picture with morse code shown at the bottom.
![image](https://user-images.githubusercontent.com/59180254/112947546-9729d380-913f-11eb-960b-060f04d01154.png)
**.... .. -.. .- .-.-.- .. -.. ..-. .-.-.- .- -- .- -. .--.-. --. -- .- .. .-.. .-.-.- -.-. --- --**
The morse code translates to: **"HIDA.IDF.AMAN@GMAIL.COM"**

That's it, now all I have to do is send the answer to this email adress.
