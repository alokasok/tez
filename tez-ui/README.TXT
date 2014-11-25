<!--
   Licensed to the Apache Software Foundation (ASF) under one or more
   contributor license agreements.  See the NOTICE file distributed with
   this work for additional information regarding copyright ownership.
   The ASF licenses this file to You under the Apache License, Version 2.0
   (the "License"); you may not use this file except in compliance with
   the License.  You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->

Dev setup instructions
----------------------
install the development dependencies nodejs, npm, grunt and bower
from webapp directory run the following commands
  * npm install
  * bower install

The timeline server (ATS) url by default points to http://localhost:8188. This can be
changed to point to another host by editing the App.AtsBaseUrl entry in the
app/scripts/app.js file.

For development run 'grunt serve'. This runs a dev server on port 9001.
navigate to http://localhost:9001 if a browser does not open automatically.
Any changes made will be live-reloaded on the browser.

For creating a distribution version, run 'grunt build'. The distributable
version will be placed under the dist directory.