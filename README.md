# umbrella :umbrella:
Umbrella repository for frontend and backend to simplify deployment.

## Running

### Production

You can run the production images with

```bash
docker-compose up
```

_That's it :sparkles:_

This will pull the images from the Github Container Registry, ensuring that you're always running the latest stable versions of the front- and backend.

### Development

For the development version, you might have to update the submodules with

```bash
git submodule update --remote
```

To ensure you are running the latest commits from both libraries.

To run the `docker-compose` setup, run

```bash
docker-compose up 
```

## License
```
   Copyright 2021 SINTEF AS

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
