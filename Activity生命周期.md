## Activity生命周期

activity 作为Android最基本的组件，当用户在浏览,退出,返回应用时activity实际上在是在其各个生命周期之间进行转换，如何在正确的生命周期内执行对应的执行操作能极大程度上节省系统资源,

也能使程序逻辑更加合理

Activity 类提供六个核心回调：onCreate()、onStart()、onResume()、onPause()、onStop() 和 onDestroy()。当 Activity 进入新状态时，系统会调用其中每个回调。

下图展示了在用户执行不同操作时Activity执行的回调
