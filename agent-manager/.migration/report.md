# Import report: Agent Manager cloud

Imported from `wso2/docs-agent-platform@2e90456b5f3a8899139c0c6c342a5738d8fc3919` by the Docusaurus importer (migration/lib/docusaurus.mjs in wso2/docs-platform).

| Measure | Count |
|---|---|
| Pages | 80 |
| Sidebar entries | 80 |
| Cloud-only pages added | 0 |
| Unlisted pages | 0 |
| Partials inlined | 2 |
| Partials copied | 0 |
| Images and files | 17 |
| Links re-pointed | 438 |
| Links marked for one Edition | 40 |
| MDX compile failures | 0 |

Cloud pages against the main line: 37 pairs, **29 differ** (see cloud-diff.md).

## Items by kind

| Kind | Count |
|---|---|
| dropped | 1 |
| link-other-edition | 40 |
| partial-inlined | 2 |
| partial | 2 |

## dropped

- `contributing`: left out: it explains how to edit the legacy Docusaurus repository; WSO2 Docs has Contribute for that

## link-other-edition

- `get-started/what-is-amp`: links to get-started/quick-start, a self-hosted only page: the link text stays plain in cloud
- `concepts/organization`: links to reference/authorization, a self-hosted only page: the link text stays plain in cloud
- `concepts/project`: links to reference/authorization, a self-hosted only page: the link text stays plain in cloud
- `concepts/agent-lifecycle`: links to guides/configure-agent-health-checks, a self-hosted only page: the link text stays plain in cloud
- `concepts/agent-lifecycle`: links to guides/configure-agent-health-checks, a self-hosted only page: the link text stays plain in cloud
- `concepts/internal-and-external-agent`: links to guides/register-an-external-a2a-agent, a self-hosted only page: the link text stays plain in cloud
- `concepts/agent-kind-and-catalog`: links to guides/configure-agent-health-checks, a self-hosted only page: the link text stays plain in cloud
- `concepts/observability`: links to reference/cli/agent, a self-hosted only page: the link text stays plain in cloud
- `concepts/observability`: links to reference/observer-mcp-server, a self-hosted only page: the link text stays plain in cloud
- `concepts/observability`: links to reference/cli/agent, a self-hosted only page: the link text stays plain in cloud
- `concepts/evaluation`: links to guides/on-your-environment, a self-hosted only page: the link text stays plain in cloud
- `concepts/agentid`: links to guides/configure-identity-providers-at-the-gateway, a self-hosted only page: the link text stays plain in cloud
- `guides/deploy-an-a2a-agent`: links to guides/cli-installation, a self-hosted only page: the link text stays plain in cloud
- `guides/deploy-an-a2a-agent`: links to guides/configure-agent-health-checks, a self-hosted only page: the link text stays plain in cloud
- `guides/deploy-an-a2a-agent`: links to reference/cli/agent, a self-hosted only page: the link text stays plain in cloud
- `guides/deploy-an-a2a-agent`: links to guides/register-an-external-a2a-agent, a self-hosted only page: the link text stays plain in cloud
- `guides/custom-evaluators`: links to get-started/quick-start, a self-hosted only page: the link text stays plain in cloud
- `guides/evaluation-monitors`: links to get-started/quick-start, a self-hosted only page: the link text stays plain in cloud
- `guides/secure-agent-endpoints-with-api-keys`: links to guides/register-an-external-a2a-agent, a self-hosted only page: the link text stays plain in cloud
- `guides/secure-agents-with-jwt-authentication`: links to guides/configure-identity-providers-at-the-gateway, a self-hosted only page: the link text stays plain in cloud
- `guides/secure-agents-with-jwt-authentication`: links to guides/configure-identity-providers-at-the-gateway, a self-hosted only page: the link text stays plain in cloud
- `guides/secure-agents-with-jwt-authentication`: links to guides/configure-identity-providers-at-the-gateway, a self-hosted only page: the link text stays plain in cloud
- `guides/register-llm-service-provider`: links to reference/cli/llm-provider, a self-hosted only page: the link text stays plain in cloud
- `guides/environment-management`: links to guides/isolation-tiers/gvisor, a self-hosted only page: the link text stays plain in cloud
- `guides/environment-management`: links to guides/isolation-tiers/kata, a self-hosted only page: the link text stays plain in cloud
- `guides/environment-management`: links to guides/on-your-environment, a self-hosted only page: the link text stays plain in cloud
- `guides/amp-instrumentation`: links to reference/sample-agents, a self-hosted only page: the link text stays plain in cloud
- `guides/amp-instrumentation`: links to guides/instrumentation-catalog, a self-hosted only page: the link text stays plain in cloud
- `guides/amp-instrumentation`: links to guides/observe-openclaw-agents, a self-hosted only page: the link text stays plain in cloud
- `guides/authorize-agent-access-to-mcp-tools`: links to guides/cli-installation, a self-hosted only page: the link text stays plain in cloud
- `guides/authorize-agent-access-to-mcp-tools`: links to reference/cli/login, a self-hosted only page: the link text stays plain in cloud
- `guides/authorize-agent-access-to-mcp-tools`: links to reference/cli/api, a self-hosted only page: the link text stays plain in cloud
- `guides/authorize-agent-access-to-mcp-tools`: links to reference/authorization, a self-hosted only page: the link text stays plain in cloud
- `tutorials/create-your-first-agent`: links to get-started/quick-start, a self-hosted only page: the link text stays plain in cloud
- `tutorials/create-your-first-agent`: links to guides/configure-agent-health-checks, a self-hosted only page: the link text stays plain in cloud
- `tutorials/promote-your-agent`: links to reference/authorization, a self-hosted only page: the link text stays plain in cloud
- `tutorials/promote-your-agent`: links to reference/cli/overview, a self-hosted only page: the link text stays plain in cloud
- `tutorials/deploy-the-a2a-notes-agent-sample`: links to get-started/quick-start, a self-hosted only page: the link text stays plain in cloud
- `tutorials/deploy-the-a2a-notes-agent-sample`: links to guides/cli-installation, a self-hosted only page: the link text stays plain in cloud
- `tutorials/deploy-the-a2a-notes-agent-sample`: links to reference/sample-agents, a self-hosted only page: the link text stays plain in cloud

## partial-inlined

- `guides/on-k3d`: guides/_partials/_amp-installation.mdx inlined with {"version":"${VERSION}","rewriteJwksForK3d":true}
- `guides/on-your-environment`: guides/_partials/_amp-installation.mdx inlined with {"version":"${VERSION}","expandRegistryConfig":true,"production":true}

## partial

- `guides/on-k3d`: the installation partial still holds props.version, props.rewriteJwksForK3d, props.expandRegistryConfig, props.production after inlining
- `guides/on-your-environment`: the installation partial still holds props.version, props.rewriteJwksForK3d, props.expandRegistryConfig, props.production after inlining
