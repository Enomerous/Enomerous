## Issue explanation (write below this line)



## Exception
* __App Name:__ Amaze File Manager
* __Package:__ com.amaze.filemanager
* __Version:__ 3.6.7
* __User Action:__ UI Error
* __Request:__ Application crash
* __OS:__ Linux Android 11 - 30
* __Device:__ f62
* __Model:__ SM-E625F
* __Product:__ f62ins
<details><summary><b>Crash log </b></summary><p>

```
java.lang.RuntimeException: An error occurred while executing doInBackground()
	at android.os.AsyncTask$4.done(AsyncTask.java:415)
	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:383)
	at java.util.concurrent.FutureTask.setException(FutureTask.java:252)
	at java.util.concurrent.FutureTask.run(FutureTask.java:271)
	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:305)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
	at java.lang.Thread.run(Thread.java:923)
Caused by: java.lang.IllegalStateException: This is not the first datapoint!
	at com.amaze.filemanager.asynchronous.services.AbstractProgressiveService.addFirstDatapoint(AbstractProgressiveService.java:244)
	at com.amaze.filemanager.asynchronous.services.ExtractService$DoWork$1.onStart(ExtractService.java:286)
	at com.amaze.filemanager.filesystem.compressed.extractcontents.helpers.ZipExtractor.extractWithFilter(ZipExtractor.kt:72)
	at com.amaze.filemanager.filesystem.compressed.extractcontents.Extractor.extractEverything(Extractor.java:82)
	at com.amaze.filemanager.asynchronous.services.ExtractService$DoWork.doInBackground(ExtractService.java:318)
	at com.amaze.filemanager.asynchronous.services.ExtractService$DoWork.doInBackground(ExtractService.java:227)
	at android.os.AsyncTask$3.call(AsyncTask.java:394)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	... 4 more

```
</details>
<hr>
- 👋 Hi, I’m @Enomerous
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Enomerous/Enomerous is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
