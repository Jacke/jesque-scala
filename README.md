# Jesque-scala wrapper

Thin resque(jesque) client wrapper for Scala.

## Configuration
Work in progress
You can try run this, with Redis 

sbt console

```scala
import com.nrmitchi.plugin.Resque
Resque.create_jobs
val thread1 = Resque.worker_try
val thread2 = Resque.worker_try1
thread1.start()
thread2.start()



## LICENSE
This software is licensed under the Apache 2 license, quoted below.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at


    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
