# RxPermissions [![Build Status](https://www.bitrise.io/app/9ce2f028d01c6c1f/status.svg?token=X-RCNlnJoO5-LhFd7vcq1Q&branch=master)](https://www.bitrise.io/app/9ce2f028d01c6c1f) [![BuildVersion](https://buildstats.info/nuget/RxPermissions)](https://www.nuget.org/packages/RxPermissions/)

Port of https://github.com/tbruyelle/RxPermissions to Xamarin.

## How to use

Have a look at [README.md](https://github.com/tbruyelle/RxPermissions/blob/master/README.md)

## How to install

### Android

Add [RxPermissions](https://www.nuget.org/packages/RxPermissions)

        PM> Install-Package RxPermissions -Version 0.9.4

## How to build

    msbuild RxPermissions.sln /t:RxPermissions /p:Configuration="Release" /p:BuildProjectReferences=false

## Contributors

[Jan Rabe](jan.rabe@kibotu.net)

### License
<pre>
Copyright 2018 Jan Rabe

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>
