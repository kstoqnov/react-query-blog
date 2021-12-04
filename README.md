## Challenges

- fetch data to use `useQuery`
- Implement per-screen background fetching indicators
- Custom hooks used to create/update/delete to use `useMutation`
- Mutations to automatically invalidate related queries
- Implement optimistic updates for mutations
- Prefetch individual posts on hover using `queryCache.prefetchQuery` OR
- Use `initialData` to show placeholder content for individual posts that pull from the parent `posts` query
- Remove per-screen background fetching indicators and instead build a global refetching indicator
- Dehydrate/hydrate the cache to and from localStorage using the `react-query/hydration` APIs

## Develop

- Run `yarn` and then `yarn dev` locally.
- Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
- **NOTE:** The "database" used in this app is simply a JSON file and thus will not work as a deployed application.

## Why Next.js?

[Read This 😁](https://gist.github.com/tannerlinsley/65ac1f0175d79d19762cf06650707830)
