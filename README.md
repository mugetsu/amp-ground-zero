# AMP ground zero with Grow

An example of building an AMP valid microsite using [Grow](https://grow.io).

## Prerequisites

At a minimum, you will need the following tools installed:

1. [Git](http://git-scm.com/)
2. [Grow](https://grow.io)

If you do not have Grow, you can install it using:

```
curl https://install.growsdk.org | bash
```

## Clone amp-ground-zero

Clone amp-ground-zero into your project directory:

```
git clone https://github.com/rd4704/amp-ground-zero.git
cd amp-ground-zero
```

## Running the development server

Prior to starting the development server, you may have to install dependencies used by your project. The `grow install` command walks you through this and tries to set up your environment for you.

The `grow run` command starts your development server. You can make changes to your project files and refresh to see them reflected immediately.

```
grow install
grow run
```

## AMP validation

In order to check if your page is AMP valid append `#development=1` in the url.

## Building

You can use the `grow build` command to build your whole site to the `build` directory. This is a good way to test and verify the generated code.

```
grow build
```

## Staging

Once you are ready to share your changes with your team, you can stage your workspace to an access-controlled web server. Running the below command will build your site and deploy it, and then provide you with a link to the staging environment.

```
grow stage
```

## Further reading

[Quick glance at Google's AMP project](http://rahul.my/blog/post/building-future-of-web-beautiful-and-high-performing-with-amp).
Official AMP project [page](https://www.ampproject.org/).
Official Grow [page](https://grow.io).
