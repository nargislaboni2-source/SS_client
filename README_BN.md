# SS Bedrock Client — Native Android Starter

## GitHub থেকে APK বানানো
1. ZIP extract করে সব ফাইল নতুন GitHub repository-তে upload করো (hidden `.github` folder-সহ)।
2. Repository → Actions → Build SS Bedrock Client APK → Run workflow।
3. Build শেষ হলে Artifacts থেকে `SS-Bedrock-Client-debug` ZIP download করো।
4. ZIP extract করে `app-debug.apk` install করো।

## ব্যবহার
1. SS Client খোলো → ENABLE FLOATING SS BUTTON চাপো।
2. Android-এর Appear on top permission চালু করো।
3. অ্যাপে ফিরে আবার ENABLE চাপো, তারপর OPEN MINECRAFT।
4. Minecraft-এর ওপর SS bubble থাকবে; চাপলে panel খুলবে।

## সীমাবদ্ধতা
এটি native overlay starter, Minecraft-এর ভেতরে code injection নয়। CPS tester শুধু নিজের panel-এর tap গোনে। Crosshair হলো screen overlay preview। FPS/ping/coordinates, game touch reading এবং resource-pack activation এখনো নেই।
