# Dashing
Run [Dashing](http://dashing.io/) in a [Docker](http://docker.io/) container.

Link: [fengal/dashing-alpine](https://registry.hub.docker.com/u/fengal/dashing-alpine/)


## Run
```docker run -d -p 8080:3030 fengal/dashing-alpine```

And point your browser to [http://localhost:8080/](http://localhost:8080/).


## Configuration
You can provide a custom dashing (including the dashboard, widgets, jobs and configuration) by mounting to the volume /dashing


```docker run -v=/my/custom/dashing:/dashing -d -p 8080:3030 fengal/dashing-alpine```

## License
Distributed under the MIT license
