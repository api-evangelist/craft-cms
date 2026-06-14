# Craft CMS GraphQL API

Craft CMS includes a built-in, auto-generated GraphQL API available since version 3.3. The schema exposes all content elements — entries, assets, categories, tags, global sets, users, and addresses — as queryable types. Access is controlled via bearer token authentication tied to named schemas configured in the control panel; a public (unauthenticated) schema can optionally be enabled.

**Endpoint:** `https://yoursite.com/actions/graphql/api`

The endpoint path can be customized via `config/routes.php`. An alternate action URL format is `/index.php?action=graphql/api`.

**Documentation:** https://craftcms.com/docs/5.x/development/graphql.html

**References:**
- Documentation: https://craftcms.com/docs/5.x/development/graphql.html
- GettingStarted: https://craftcms.com/docs/5.x/development/graphql.html#getting-started
- GitHub Source: https://github.com/craftcms/cms/tree/main/src/gql
- GraphiQL IDE: Available at **GraphQL → GraphiQL** inside the Craft control panel
