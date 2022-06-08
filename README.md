# RandomFlutterKnowledge
This repo has random flutter knowledge that's worth noting when coding. Feel free to contribute.


1. Always add version number in pubspec.yaml because the packages and their dependencies might not be updated together and this will surel break your code.

2. Remember Future.wait([future1, future2]). Can be used in used in ititState() to wait for futures.

3. When using FutureBuilder, get the future first and then use it. Else it'll be called multiple times. Follow the answer here https://stackoverflow.com/questions/72540468/getmaterialapp-home-widget-is-being-called-multiple-times
