Step by step to build and work python
1. Install and setup envirenment python on your platform
2. Install web server (Apache by wramp)
    Modifile httpd.conf
        AddHandler cgi-script .cgi .py
        Options Indexes FollowSymLinks ExecCGI
3. Create your app in ${INSTALL_DIR}/www
    index.py
        #!c:/Python37/python.exe
        print("Content-Type: text/html")
        print()
        print("<html><head><title>Python</title></head>")
        print("<body><h1>Hello world</h1></body></html>")
