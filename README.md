# CI detection fixture

THE TRAP. A perfectly valid Jenkinsfile in a C++/CMake repo. The stack gate fires BEFORE any CI file is opened, so this says nothing about Jenkins detection. Recognised kinds are node/typescript/angular, go, java, python, rust, ruby, php, dotnet, elixir - everything ELSE lands here. Run it once so you recognise the message.

Expected verdict line in the Octiq chat:

    Tests not run - edits on <stack> repositories do not run tests yet
