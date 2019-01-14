# ServiceTest
steps----
        1) Create a class as child of service class which is abstract class having an abstract method onBind()
        2) major methods -
                          onCreate()
                          onStartCommand()
                          onDestroy()
        3) in MaimActivity 
                           var i = Intent(this@MainActivity, MyService::class.java)
                             startService(i)
                           
                          var i = Intent(this@MainActivity,  MyService::class.java)
                             stopService(i)
        
