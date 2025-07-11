# Speech API REST server

Built version of https://github.com/depau/SAPISpeechServer

https://file.wf/1ade1198.zip


Windows application server

If you want to run this on Windows, or if you're doing things manually on Wine, you can download executables from the latest successful GitHub Actions build.

    Visit https://github.com/depau/SAPISpeechServer/actions/workflows/dotnet.yml [or use the file.wf link]
    Click on the latest successful build
    Scroll down to the "Artifacts" section and download the SAPISpeechServer file
    Launch SAPISpeechServer.exe
        To run it on a different port, run SAPISpeechServer.exe --urls http://localhost:5000 from the command line

It should automatically detect all 32-bit voices. For 64-bit voices you'll need to rebuild it from source.
