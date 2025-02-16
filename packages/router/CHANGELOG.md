# `@remix-run/router`

## 1.0.2-pre.0

### Patch Changes

- fix: throw error when receiving invalid path object ([#9375](https://github.com/remix-run/react-router/pull/9375))
- fix: reset `actionData` after successful action redirect ([#9334](https://github.com/remix-run/react-router/pull/9334))
- fix: update `matchPath` to avoid false positives on dash-separated segments ([#9300](https://github.com/remix-run/react-router/pull/9300))
- fix: Strengthen `RouteObject`/`RouteProps` types and throw on `index` routes with `children` ([#9366](https://github.com/remix-run/react-router/pull/9366))

## 1.0.1

### Patch Changes

- Preserve state from `initialEntries` ([#9288](https://github.com/remix-run/react-router/pull/9288))
- Preserve `?index` for fetcher get submissions to index routes ([#9312](https://github.com/remix-run/react-router/pull/9312))

## 1.0.0

This is the first stable release of `@remix-run/router`, which provides all the underlying routing and data loading/mutation logic for `react-router`. You should _not_ be using this package directly unless you are authoring a routing library similar to `react-router`.

For an overview of the features provided by `react-router`, we recommend you go check out the [docs][rr-docs], especially the [feature overview][rr-feature-overview] and the [tutorial][rr-tutorial].

For an overview of the features provided by `@remix-run/router`, please check out the [`README`][remix-router-readme].

[rr-docs]: https://reactrouter.com/
[rr-feature-overview]: https://reactrouter.com/en/v6.4.0/start/overview
[rr-tutorial]: https://reactrouter.com/en/v6.4.0/start/tutorial
[remix-router-readme]: https://github.com/remix-run/react-router/blob/main/packages/router/README.md
