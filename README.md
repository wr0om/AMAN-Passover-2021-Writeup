<p align="center">
     AMAN Challenge Writeup
</p>
<p align="center">
 <a href="https://www.idf.il/%D7%90%D7%AA%D7%A8%D7%99%D7%9D/%D7%90%D7%92%D7%A3-%D7%94%D7%9E%D7%95%D7%93%D7%99%D7%A2%D7%99%D7%9F/2021/%D7%97%D7%99%D7%93%D7%AA-%D7%9E%D7%95%D7%93%D7%99%D7%A2%D7%99%D7%9F-%D7%90%D7%9E%D7%9F-%D7%A4%D7%A1%D7%97-%D7%90%D7%AA%D7%92%D7%A8-%D7%A6%D7%94%D7%9C-%D7%97%D7%99%D7%93%D7%94/">
<img align="center" alt="wr0om | AMAN-CHALLENGE" width="120px" src="https://upload.wikimedia.org/wikipedia/commons/6/68/AmanLogo.svg"/>
</p>


## First Stage
We start the challenge by getting a translation of the popular song Dayenu (דיינו) from Hebrew to English.
As we read it, we can notice spelling mistakes throughout the song.

```
If He had brought us out from Egypt and had not carried out judgments against them

!Dayenu, it would have sufficed us-

If he had carried out judgments against them, and not against their idols

!Dayenu, it would have sufficed us-

and so forth...
```
For example, "sufficed" (the #1 spelling mistake) becomes "sufliced" in the song - and so forth.
let's list all the mistakes by order:
1. sufficed – sufliced
2. had - hed
3. sea - tea
4. ...

We can notice that all of the spelling mistakes are mistakes of 1 misplaced letter - ergo 'l' instead of an 'f' for sufficed.
let's make a string using these mistakes, we start with the letter 'l'.
As we see, we get the string "letmypeoplego".

At the bottom of the page, below the song, we see - "Who said ____________?"

We place the word we found - **Who said let my people go? - Moses**.

We get a link - _www.idf.il/_____/י/_.
We place "Moses" inside the link (in Hebrew like stated below - "משה"),
and continue to the next stage located at **www.idf.il/משה/י/**.

## Second Stage
On the next page we get this sentence:
```
... יש מי שחושב שסיפור יציאת מצרים הוא פנטזיה, אך תוך כדי ויכוח טוב, תוכלו להראות את העובדה הבאה ולהוכיח, שאין זו
And the string: "בט.טזחובד, גא.____טו"
```

"אין זו אגדה" - is a known saying referenced in the first sentence given (a phrase from ["Altneuland"](https://en.wikipedia.org/wiki/The_Old_New_Land) - book by Theodor Herzl).

We place the word "אגדה" in the given string: *"בט.טזחובד, גא.**אגדה**טו"*.
Underneath the string there is another hint: 

"בסמוך תמצאו עיר שמסמלת ניצחון כואב" - near you will find a city that symbolizes a painful victory.

From the format of the given string and that hint, we can assume the string is coordinates.
By using Gematria (where each character is equal to a number), we get these coordinates: **29.978624, 31.134596**.
which leads us to The Great Pyramid of Giza.

![image](https://user-images.githubusercontent.com/59180254/112946982-df94c180-913e-11eb-861d-bde497257d19.png)

Close to the pyramid, we can spot a city called "6th of October".
This city's name commemorates the commencement of the 1973 Arab–Israeli War on 6 October 1973 - which was a painful victory for Israel (the hint from earlier checks out).

![image](https://user-images.githubusercontent.com/59180254/112949244-ae69c080-9141-11eb-8b5f-86b7b2afc56a.png)

So that's it? did we finish the challenge? not yet.
We still haven't found a way to send the answer to AMAN.

By searching around on the site, I stumbled upon this image with morse code shown at the bottom of it.

![image](https://user-images.githubusercontent.com/59180254/112947546-9729d380-913f-11eb-960b-060f04d01154.png)

```.... .. -.. .- .-.-.- .. -.. ..-. .-.-.- .- -- .- -. .--.-. --. -- .- .. .-.. .-.-.- -.-. --- --```

The morse code translates to **"HIDA.IDF.AMAN@GMAIL.COM"**

That's it, now all we have to do is send the answer (The Great Pyramid of Giza) to this email address.
