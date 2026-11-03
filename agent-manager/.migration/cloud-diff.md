# Agent Manager: Cloud pages against the main line

The main line is seeded from the source's Next tree (`docs`); pages found only in its Cloud snapshot (`versioned_docs/version-cloud`) are added and marked Cloud only. A Cloud page that the Next tree also has keeps Next's text on the main line, so the Cloud Edition shows Next's wording until the team reconciles the two. This report lists those pairs so the team can decide each one by PR. Imported from `wso2/docs-agent-platform@5278a51b2e7d5cd7681e81d3270ac536cf860add`.

- Pairs: 37 (10 identical, **27 differ**)
- Cloud-only pages added: 0

| Cloud page (legacy) | Main-line page | Word F1 | Lines +/− | |
|---|---|---|---|---|
| [concepts/agent-kind-and-catalog](https://wso2.com/agent-platform/docs/cloud/concepts/agent-kind-and-catalog/) | `docs/concepts/agent-kind-and-catalog.mdx` | 1.000 | 0 | identical |
| [concepts/agent-lifecycle](https://wso2.com/agent-platform/docs/cloud/concepts/agent-lifecycle/) | `docs/concepts/agent-lifecycle.mdx` | 0.910 | +6 / −4 | **differs** |
| [concepts/agentid](https://wso2.com/agent-platform/docs/cloud/concepts/agentid/) | `docs/concepts/agentid.mdx` | 0.942 | +5 / −14 | **differs** |
| [concepts/deployment-pipeline](https://wso2.com/agent-platform/docs/cloud/concepts/deployment-pipeline/) | `docs/concepts/deployment-pipeline.mdx` | 0.827 | +2 / −2 | **differs** |
| [concepts/environment](https://wso2.com/agent-platform/docs/cloud/concepts/environment/) | `docs/concepts/environment.mdx` | 1.000 | 0 | identical |
| [concepts/evaluation](https://wso2.com/agent-platform/docs/cloud/concepts/evaluation/) | `docs/concepts/evaluation.mdx` | 0.995 | +1 / −1 | **differs** |
| [concepts/gateway](https://wso2.com/agent-platform/docs/cloud/concepts/gateway/) | `docs/concepts/gateway.mdx` | 1.000 | 0 | identical |
| [concepts/internal-and-external-agent](https://wso2.com/agent-platform/docs/cloud/concepts/internal-and-external-agent/) | `docs/concepts/internal-and-external-agent.mdx` | 0.957 | +0 / −1 | **differs** |
| [concepts/llm-service-provider](https://wso2.com/agent-platform/docs/cloud/concepts/llm-service-provider/) | `docs/concepts/llm-service-provider.mdx` | 1.000 | 0 | identical |
| [concepts/mcp-proxy](https://wso2.com/agent-platform/docs/cloud/concepts/mcp-proxy/) | `docs/concepts/mcp-proxy.mdx` | 0.965 | +1 / −3 | **differs** |
| [concepts/observability](https://wso2.com/agent-platform/docs/cloud/concepts/observability/) | `docs/concepts/observability.mdx` | 0.785 | +2 / −43 | **differs** |
| [concepts/organization](https://wso2.com/agent-platform/docs/cloud/concepts/organization/) | `docs/concepts/organization.mdx` | 0.976 | +2 / −2 | **differs** |
| [concepts/project](https://wso2.com/agent-platform/docs/cloud/concepts/project/) | `docs/concepts/project.mdx` | 0.877 | +1 / −3 | **differs** |
| [get-started/what-is-amp](https://wso2.com/agent-platform/docs/cloud/get-started/what-is-amp/) | `docs/get-started/what-is-amp.mdx` | 0.646 | +3 / −35 | **differs** |
| [guides/amp-instrumentation](https://wso2.com/agent-platform/docs/cloud/guides/amp-instrumentation/) | `docs/guides/platform-administration/amp-instrumentation.mdx` | 0.888 | +3 / −56 | **differs** |
| [guides/authorize-agent-access-to-mcp-tools](https://wso2.com/agent-platform/docs/cloud/guides/authorize-agent-access-to-mcp-tools/) | `docs/guides/agent-identity-and-access-management/authorize-agent-access-to-mcp-tools.mdx` | 0.773 | +50 / −97 | **differs** |
| [guides/configure-agent-llm-configuration](https://wso2.com/agent-platform/docs/cloud/guides/configure-agent-llm-configuration/) | `docs/guides/platform-administration/configure-agent-llm-configuration.mdx` | 0.994 | +2 / −2 | **differs** |
| [guides/configure-agent-mcp-proxies](https://wso2.com/agent-platform/docs/cloud/guides/configure-agent-mcp-proxies/) | `docs/guides/agent-identity-and-access-management/configure-agent-mcp-proxies.mdx` | 0.863 | +0 / −84 | **differs** |
| [guides/configure-cors-for-agent-endpoints](https://wso2.com/agent-platform/docs/cloud/guides/configure-cors-for-agent-endpoints/) | `docs/guides/securing-agent-endpoints/configure-cors-for-agent-endpoints.mdx` | 1.000 | 0 | identical |
| [guides/configure-trace-sampling](https://wso2.com/agent-platform/docs/cloud/guides/configure-trace-sampling/) | `docs/guides/evaluation-and-observability/configure-trace-sampling.mdx` | 1.000 | 0 | identical |
| [guides/custom-evaluators](https://wso2.com/agent-platform/docs/cloud/guides/custom-evaluators/) | `docs/guides/evaluation-and-observability/custom-evaluators.mdx` | 0.986 | +1 / −1 | **differs** |
| [guides/deploy-an-a2a-agent](https://wso2.com/agent-platform/docs/cloud/guides/deploy-an-a2a-agent/) | `docs/guides/deploy-an-a2a-agent.mdx` | 0.857 | +2 / −53 | **differs** |
| [guides/environment-management](https://wso2.com/agent-platform/docs/cloud/guides/environment-management/) | `docs/guides/platform-administration/environment-management.mdx` | 0.637 | +26 / −109 | **differs** |
| [guides/evaluation-monitors](https://wso2.com/agent-platform/docs/cloud/guides/evaluation-monitors/) | `docs/guides/evaluation-and-observability/evaluation-monitors.mdx` | 0.988 | +1 / −1 | **differs** |
| [guides/register-llm-service-provider](https://wso2.com/agent-platform/docs/cloud/guides/register-llm-service-provider/) | `docs/guides/platform-administration/register-llm-service-provider.mdx` | 0.969 | +3 / −3 | **differs** |
| [guides/register-mcp-proxy](https://wso2.com/agent-platform/docs/cloud/guides/register-mcp-proxy/) | `docs/guides/platform-administration/register-mcp-proxy.mdx` | 0.992 | +2 / −2 | **differs** |
| [guides/retrieve-agentid-for-externally-hosted-agents](https://wso2.com/agent-platform/docs/cloud/guides/retrieve-agentid-for-externally-hosted-agents/) | `docs/guides/agent-identity-and-access-management/retrieve-agentid-for-externally-hosted-agents.mdx` | 1.000 | 0 | identical |
| [guides/secure-agent-endpoints-with-api-keys](https://wso2.com/agent-platform/docs/cloud/guides/secure-agent-endpoints-with-api-keys/) | `docs/guides/securing-agent-endpoints/secure-agent-endpoints-with-api-keys.mdx` | 0.971 | +0 / −2 | **differs** |
| [guides/secure-agents-with-jwt-authentication](https://wso2.com/agent-platform/docs/cloud/guides/secure-agents-with-jwt-authentication/) | `docs/guides/securing-agent-endpoints/secure-agents-with-jwt-authentication.mdx` | 0.984 | +3 / −3 | **differs** |
| [guides/use-agentid-in-platform-hosted-agents](https://wso2.com/agent-platform/docs/cloud/guides/use-agentid-in-platform-hosted-agents/) | `docs/guides/agent-identity-and-access-management/use-agentid-in-platform-hosted-agents.mdx` | 0.912 | +29 / −46 | **differs** |
| [tutorials/build-a-ballerina-agent](https://wso2.com/agent-platform/docs/cloud/tutorials/build-a-ballerina-agent/) | `docs/tutorials/build-a-ballerina-agent.mdx` | 1.000 | 0 | identical |
| [tutorials/create-your-first-agent](https://wso2.com/agent-platform/docs/cloud/tutorials/create-your-first-agent/) | `docs/tutorials/create-your-first-agent.mdx` | 0.962 | +16 / −21 | **differs** |
| [tutorials/deploy-the-a2a-notes-agent-sample](https://wso2.com/agent-platform/docs/cloud/tutorials/deploy-the-a2a-notes-agent-sample/) | `docs/tutorials/deploy-the-a2a-notes-agent-sample.mdx` | 0.933 | +1 / −36 | **differs** |
| [tutorials/give-the-agent-real-tools](https://wso2.com/agent-platform/docs/cloud/tutorials/give-the-agent-real-tools/) | `docs/tutorials/give-the-agent-real-tools.mdx` | 1.000 | 0 | identical |
| [tutorials/govern-the-model](https://wso2.com/agent-platform/docs/cloud/tutorials/govern-the-model/) | `docs/tutorials/govern-the-model.mdx` | 0.954 | +10 / −30 | **differs** |
| [tutorials/observe-first-agent](https://wso2.com/agent-platform/docs/cloud/tutorials/observe-first-agent/) | `docs/tutorials/observe-first-agent.mdx` | 1.000 | 0 | identical |
| [tutorials/promote-your-agent](https://wso2.com/agent-platform/docs/cloud/tutorials/promote-your-agent/) | `docs/tutorials/promote-your-agent.mdx` | 0.968 | +13 / −23 | **differs** |

## Differences

Each diff reads from the main-line text (`-`) to the Cloud text (`+`), front matter left out.

### concepts/agent-lifecycle

Main-line page `docs/concepts/agent-lifecycle.mdx`; word F1 0.910.

<details><summary>Diff</summary>

```diff
--- main line: concepts/agent-lifecycle.mdx
+++ Cloud: concepts/agent-lifecycle.mdx
@@ -21,9 +21,11 @@ Moving an agent from registered to running in production is a sequence of distin
 | Create | `amp:agent:create` | Registers the agent in a project. |
 | Build | `amp:agent:build` | Builds a deployable artifact from the agent's source (platform-hosted only). |
-| Deploy | `amp:agent:env-non-production` | Deploys a built artifact to the lowest [environment](./environment.mdx) in the project's [pipeline](./deployment-pipeline.mdx). Needs `amp:agent:env-production` **as well** if that environment is flagged as production. |
-| Promote | `amp:agent:env-non-production` | Moves a deployed version to the next environment in the pipeline. Needs `amp:agent:env-production` **as well** when the target is a production environment. |
-| Suspend | `amp:agent:suspend` | Stops a deployed agent without deleting it. Needs the target environment's tier scope too — both of them, in production. |
+| Deploy (non-production) | `amp:agent:deploy-non-production` | Deploys a built artifact to a non-production [environment](./environment.mdx). |
+| Deploy (production) | `amp:agent:deploy-production` | Deploys to a production environment — a separate permission from non-production deploys. |
+| Promote | `amp:agent:promote` | Moves a deployed version to the next environment in the project's [deployment pipeline](./deployment-pipeline.mdx). |
+| Rollback | `amp:agent:rollback` | Reverts an environment to a previously deployed version. |
+| Suspend | `amp:agent:suspend` | Stops a deployed agent without deleting it. |
 
-Splitting production deploys from non-production ones means someone can be trusted to push to staging without being trusted to push straight to production — the same separation the [deployment pipeline](./deployment-pipeline.mdx) enforces at the environment level. The production grant stacks on the non-production one rather than replacing it: reaching production means holding both, and holding `amp:agent:env-production` alone reaches nothing.
+Splitting production deploys from non-production ones means someone can be trusted to push to staging without being trusted to push straight to production — the same separation the [deployment pipeline](./deployment-pipeline.mdx) enforces at the environment level.
 
 ## Deployment Status Per Environment
```

</details>

### concepts/agentid

Main-line page `docs/concepts/agentid.mdx`; word F1 0.942.

<details><summary>Diff</summary>

```diff
--- main line: concepts/agentid.mdx
+++ Cloud: concepts/agentid.mdx
@@ -11,6 +11,6 @@ AgentID is built on two pieces working together.
 
 1. **A dedicated identity provider for every environment.** Every environment gets its own
-   [ThunderID](https://thunderid.dev/) instance, created as part of setting up that environment. This instance is
-   completely separate from every other environment's [ThunderID](https://thunderid.dev/) instance, and from the Thunder
+   ThunderID instance, created as part of setting up that environment. This instance is
+   completely separate from every other environment's ThunderID instance, and from the Thunder
    identity provider that Agent Manager itself uses for console and API login.
 2. **One OAuth 2.0 identity per agent, per environment.** When an agent is created, Agent Manager
@@ -57,6 +57,5 @@ provisioning, its `client_id`, `client_secret`, token endpoint, and scopes are i
 pod as environment variables, backed by a Kubernetes secret. There is no manual retrieval step,
 though your agent's own code does need a small amount of logic to use those environment
-variables. See [Use AgentID in a Platform-Hosted Agent](../guides/use-agentid-in-platform-hosted-agents.mdx)
-for the environment variables involved and the code your agent needs to mint and use a token.
+variables.
 
 ### Externally-Hosted Agents
@@ -65,7 +64,5 @@ For an agent that runs outside the platform, Agent Manager has no workload to in
 credentials into. Instead, the agent's operator generates the credential from the agent's page
 in the console: the `client_id` and a freshly minted `client_secret` are shown once, ready to
-copy into the agent's own configuration. See
-[Retrieve AgentID Credentials for an Externally-Hosted Agent](../guides/retrieve-agentid-for-externally-hosted-agents.mdx)
-for the retrieval flow.
+copy into the agent's own configuration.
 
 ## Provisioning and Retry
@@ -116,13 +113,7 @@ already issued before the revoke: those remain valid until they naturally expire
 has no way to instantly invalidate a token it has already handed out.
 
-## What's Next
-
-- [Access an environment's ThunderID console](../guides/environment-management.mdx#access-the-environment-thunderid-console)
-- [Use AgentID in a Platform-Hosted Agent](../guides/use-agentid-in-platform-hosted-agents.mdx)
-- [Retrieve AgentID Credentials for an Externally-Hosted Agent](../guides/retrieve-agentid-for-externally-hosted-agents.mdx)
-
 :::note
 AgentID's per-environment ThunderID instances are separate from the
-[identity providers you configure on a gateway](../guides/configure-identity-providers-at-the-gateway.mdx)
+identity providers you configure on a gateway
 to secure an agent's own inbound endpoint. Those protect calls coming into an agent. AgentID is
 about the identity an agent presents when it calls out to the gateway.
```

</details>

### concepts/deployment-pipeline

Main-line page `docs/concepts/deployment-pipeline.mdx`; word F1 0.827.

<details><summary>Diff</summary>

```diff
--- main line: concepts/deployment-pipeline.mdx
+++ Cloud: concepts/deployment-pipeline.mdx
@@ -10,6 +10,6 @@ Agent Manager's deployment pipelines are [OpenChoreo Deployment Pipelines](https
 
 - An agent version is deployed to one environment at a time, following the order the project's pipeline allows.
-- Moving an agent from one environment to the next is a **promotion**, permissioned separately from the initial deploy.
-- Deploying, promoting, and changing an agent's deployment state each require a scope for the *kind* of environment being targeted: `amp:agent:env-non-production` for ordinary environments, and `amp:agent:env-production` **in addition to it** for those flagged `isProduction` — the production grant stacks on the non-production one rather than replacing it, and reaches nothing on its own. Changing the deployment state also requires `amp:agent:suspend`, the capability beside the environment axis. So the access-control boundary follows the production flag rather than a position in the pipeline — someone can be allowed to push all the way to staging without being allowed into production, whatever the pipeline's shape.
+- Moving an agent from one environment to the next is a **promotion** — a distinct, permissioned action (`amp:agent:promote`) from the initial deploy.
+- Because deploying to a production environment is a separate permission (`amp:agent:deploy-production`) from deploying to a non-production one (`amp:agent:deploy-non-production`), a pipeline's promotion order is also an access-control boundary: someone can be allowed to push to staging without being allowed to push straight to production.
 
 ## Relationship to Projects and Environments
```

</details>

### concepts/evaluation

Main-line page `docs/concepts/evaluation.mdx`; word F1 0.995.

<details><summary>Diff</summary>

```diff
--- main line: concepts/evaluation.mdx
+++ Cloud: concepts/evaluation.mdx
@@ -219,5 +219,5 @@ For a step-by-step walkthrough of creating custom evaluators in the AMP Console,
 
 :::note Network access
-On deployments where the evaluation-job NetworkPolicy is enabled and the cluster's CNI enforces it (see [Cluster Requirements](../guides/on-your-environment.mdx#cluster-requirements)), custom evaluator code runs with restricted network egress — it can reach only what evaluation itself needs (trace data, the LLM gateway for LLM-Judge evaluators, and the scoring endpoint), not arbitrary external services. Design evaluators that don't depend on unrelated outbound network calls regardless, since this isn't guaranteed on every deployment.
+Custom evaluator code runs with restricted network egress — it can reach only what evaluation itself needs (trace data, the LLM gateway for LLM-Judge evaluators, and the scoring endpoint), not arbitrary external services. Design evaluators that don't depend on unrelated outbound network calls.
 :::
 
```

</details>

### concepts/internal-and-external-agent

Main-line page `docs/concepts/internal-and-external-agent.mdx`; word F1 0.957.

<details><summary>Diff</summary>

```diff
--- main line: concepts/internal-and-external-agent.mdx
+++ Cloud: concepts/internal-and-external-agent.mdx
@@ -17,5 +17,4 @@ The practical differences that follow from this:
 - **No deploy or promote step.** There's nothing for the platform to deploy, so [AgentID](./agentid.mdx) credential provisioning for every environment in the organization begins as soon as the agent is registered, rather than being tied to a deploy.
 - **You wire configuration in yourself.** Since there's no pod to inject into, the platform instead hands you connection details to configure — an API key and OTel endpoint for instrumentation, and endpoint URLs plus API keys for any LLM Service Provider or MCP Proxy the agent uses.
-- **Callers reach it at its own address.** The exception is an externally-hosted A2A agent, which can be routed through an environment's gateway so that gateway API keys, CORS, and authentication apply to it. See [Register an External A2A Agent](../guides/register-an-external-a2a-agent.mdx).
 - **Observability requires instrumenting it.** No traces appear until the agent is connected via the `amp-instrumentation` package (or the manual `init_otel()` path) — see [AMP Instrumentation](../guides/amp-instrumentation.mdx).
 
```

</details>

### concepts/mcp-proxy

Main-line page `docs/concepts/mcp-proxy.mdx`; word F1 0.965.

<details><summary>Diff</summary>

```diff
--- main line: concepts/mcp-proxy.mdx
+++ Cloud: concepts/mcp-proxy.mdx
@@ -13,7 +13,5 @@ An MCP proxy is multi-environment. You attach one or more endpoints to it, and e
 ### Where configuration lives
 
-The endpoint is the unit of configuration. Its upstream connection, capabilities, access control, rewrite, security are all stored on the endpoint, not on the environment. An environment is deployed with the configuration of the endpoint it is bound to, so several environments can share one endpoint's config, and editing that endpoint changes all of them. To vary settings across environments, put them on separate endpoints. The one exception is **scopes** (used for [agent authorization](../guides/authorize-agent-access-to-mcp-tools.mdx)): they are defined once for the whole proxy and apply across every endpoint and environment.
+The endpoint is the unit of configuration. Its upstream connection, capabilities, access control, rewrite, security are all stored on the endpoint, not on the environment. An environment is deployed with the configuration of the endpoint it is bound to, so several environments can share one endpoint's config, and editing that endpoint changes all of them. To vary settings across environments, put them on separate endpoints. The one exception is **scopes** (used for agent authorization): they are defined once for the whole proxy and apply across every endpoint and environment.
 
 Each agent resolves the proxy's per-environment endpoint at its own deploy time, so changing a proxy does not automatically redeploy the agents that use it; they pick up the change on their next deployment.
-
-For the console walkthrough of registering a proxy, see [Register an MCP Proxy](../guides/register-mcp-proxy.mdx).
```

</details>

### concepts/observability

Main-line page `docs/concepts/observability.mdx`; word F1 0.785.

<details><summary>Diff</summary>

```diff
--- main line: concepts/observability.mdx
+++ Cloud: concepts/observability.mdx
@@ -66,5 +66,5 @@ In the Setup Agent panel, select a **Token Duration** and click **Generate**. Co
 
 ```bash
-export AMP_OTEL_ENDPOINT="http://default-default.gateway.localhost:19080/otel"
+export AMP_OTEL_ENDPOINT="<INSTRUMENTATION_URL>"
 export AMP_AGENT_API_KEY="<your-generated-api-key>"
 ```
@@ -105,44 +105,3 @@ By default every trace an agent produces is exported. At high request rates that
 Once traces start flowing in, you can explore them in the AMP Console under your agent's sidebar:
 
-- **Observability** → **Traces**: search and inspect individual traces by time range, trace ID, or the filters below. Expand a trace to see LLM spans, tool spans, and agent reasoning steps.
-
-### Filter traces
-
-Agent Manager provides the following trace filters:
-
-| Filter | Matches traces |
-|---|---|
-| Status | That ended in an error, or that succeeded. The status comes from the trace's root span. |
-| Duration | That took at least the given time to complete. |
-| Tokens | That used at least the given number of tokens in total, across all LLM calls. |
-| Span count | That have at least the given number of spans, or steps. |
-| Model | That called a model whose name contains the given text. For example, `gpt-4o` also matches `gpt-4o-mini`. |
-| Conversation ID | That belong to the given conversation, or that have no conversation ID. |
-| Tool | That called a tool whose name contains the given text. |
-| Tool failed | Where a tool call failed. With Tool set, only traces where that tool failed. |
-| MCP server | That used an MCP server whose name contains the given text. |
-
-`amctl` and the observer MCP server accept the same filters. See [`amctl agent traces`](../reference/cli/agent.mdx#amctl-agent-traces) and the [observer MCP server's tools](../reference/observer-mcp-server.mdx#available-tools).
-
-#### In the Console
-
-1. Open the agent and navigate to **Observability** → **Traces**, then select the environment and time range.
-2. Select **Errors** or **Success** in the **Status** toggle.
-
-    ![Trace list with the Status toggle, filter chips, Go to trace ID, and Advanced Filters above the list](../img/observability/trace-filter-bar.png)
-
-3. Click **Advanced Filters**, set the filters you need, and click **Filter**. Each filter appears as a chip above the list. Remove a chip to clear that filter.
-
-    ![Advanced Filters panel with Tokens at least set to 9k and Tool called set to search_issues](../img/observability/trace-advanced-filters.png)
-
-4. To open a specific trace, enter its ID in **Go to trace ID** and press Enter.
-
-The page URL carries the filters and time range, so you can share a filtered view by copying it.
-
-**Export** downloads the matching traces with full span data, up to the list's page size of 10. To export more, use [`amctl agent traces export`](../reference/cli/agent.mdx#amctl-agent-traces-export).
-
-#### When results look incomplete
-
-- **The list stops early.** On a busy agent the search can stop before it covers the whole time range, and the list shows **Searched as far as** a time. Scroll down to load more, or narrow the time range.
-- **Conversation ID, tool, or MCP server filters match nothing.** These filters depend on what the agent's traces record. Auto-instrumented agents record them. For an agent that emits its own spans, see [Making traces filterable](../guides/amp-instrumentation.mdx#making-traces-filterable).
-- **A large trace never matches.** For performance, the **Model** filter only checks traces with up to 100 spans, and the tool and MCP server filters only check traces with up to 200 spans.
+- **OBSERVABILITY → Traces** — search and inspect individual traces by time range or correlation ID; expand a trace to see LLM spans, tool spans, and agent reasoning steps
```

</details>

### concepts/organization

Main-line page `docs/concepts/organization.mdx`; word F1 0.976.

<details><summary>Diff</summary>

```diff
--- main line: concepts/organization.mdx
+++ Cloud: concepts/organization.mdx
@@ -20,5 +20,5 @@ Access control in Agent Manager is defined at the organization level and nowhere
 ### One Permission Model, Every Entry Point
 
-Every action in the organization is authorized against an OAuth 2.0 scope named `amp:<resource>:<action>`(ex:- `amp:project:read`, `amp:agent:build`, `amp:gateway:create`).Scopes are issued as claims on an access token by the platform's identity provider. The same scope gates the same capability whether you reach the platform through the Console, the REST API, or the MCP servers. The full catalog is in the [Authorization reference](../reference/authorization.mdx).
+Every action in the organization is authorized against an OAuth 2.0 scope named `amp:<resource>:<action>`(ex:- `amp:project:read`, `amp:agent:build`, `amp:gateway:create`).Scopes are issued as claims on an access token by the platform's identity provider. The same scope gates the same capability whether you reach the platform through the Console, the REST API, or the MCP servers.
 
 :::note
@@ -41,5 +41,5 @@ The split between those last two is the useful part: an AI Lead governs *what ag
 ### Production Is a Separate Permission
 
-Acting on an environment isn't one permission — it's two. `amp:agent:env-non-production` and `amp:agent:env-production` are distinct scopes checked alongside the operation's own, so a Developer can deploy, promote, and iterate freely across every environment that isn't flagged as production, while production stays with Platform Engineers and admins.
+Deploying an agent isn't one permission it's two. `amp:agent:deploy-non-production` and `amp:agent:deploy-production` are distinct scopes, so a Developer can iterate freely in development and staging while production deployment, promotion, and suspension stay with Platform Engineers and admins.
 
 This is what makes a [Deployment Pipeline](./deployment-pipeline.mdx) a real control rather than a convention, the pipeline defines the path an agent takes through environments, and the permission split decides who is allowed to move it along that path.
```

</details>

### concepts/project

Main-line page `docs/concepts/project.mdx`; word F1 0.877.

<details><summary>Diff</summary>

```diff
--- main line: concepts/project.mdx
+++ Cloud: concepts/project.mdx
@@ -7,7 +7,5 @@ A Project is the primary container for your agents in WSO2 Agent Manager. You cr
 An Agent Manager Project is an [OpenChoreo Project](https://openchoreo.dev/docs/concepts/developer-abstractions/#project). A project groups everything that makes up one application or business capability. So you'd put the agents that work together in the same project, rather than putting every agent in your organization into one.
 
-The grouping is more than a label. Each project's workloads run in their own Kubernetes namespace, provisioned for each project and environment pair, so agents in different projects do not share a runtime namespace.
-
-That separation is a runtime one rather than an access-control one. Permissions are granted organization-wide and not per project, so a role that can read or create agents in one project carries the same permission across every project in the organization. See [Authorization](../reference/authorization.mdx) for the scopes that are actually evaluated. Use projects to organize related agents and to govern how they promote through environments, rather than to control which users can reach which agents.
+The grouping is more than a label. Each project gets its own namespace, network boundary, and security policies, so agents in one project are genuinely isolated from agents in another.
 
 ### How Agents Map to OpenChoreo Components
```

</details>

### get-started/what-is-amp

Main-line page `docs/get-started/what-is-amp.mdx`; word F1 0.646.

<details><summary>Diff</summary>

```diff
--- main line: get-started/what-is-amp.mdx
+++ Cloud: get-started/what-is-amp.mdx
@@ -19,41 +19,9 @@ Built on [OpenChoreo](https://github.com/openchoreo/openchoreo) for internal age
 - **External Agent Support** - Monitor and govern externally deployed agents alongside internal ones
 
-## Components
-
-| Component                                | Description                                                                                       |
-|------------------------------------------|---------------------------------------------------------------------------------------------------|
-| **amp-instrumentation**                  | Python package (PyPI) for instrumenting externally-hosted agents and for manual instrumentation   |
-| **amp-evaluation** *(experimental)*      | Python SDK for building custom evaluators and running evaluation pipelines                        |
-| **amp-console**                          | Web-based management console for the platform                                                     |
-| **amp-api**                              | Backend API powering the control plane                                                            |
-| **amp-trace-observer**                   | API for querying and analyzing trace data                                                         |
-| **amp-python-instrumentation-provider**  | Kubernetes init container that auto-instruments platform-hosted Python agents                     |
-
-## Helm Charts
-
-Deploy WSO2 Agent Manager on Kubernetes using our Helm charts:
-
-| Chart | Description |
-|-------|-------------|
-| `wso2-agent-manager` | Main platform deployment |
-| `wso2-amp-platform-resources-extension` | Platform resources and build workflows for OpenChoreo |
-| `wso2-amp-observability-extension` | Observability stack extension for OpenChoreo |
-| `wso2-amp-evaluation-extension` | Evaluation engine extension for Agent Manager |
-
 ## Getting Started
 
-For installation instructions and a step-by-step guide, see the [Quick Start Guide](./quick-start.mdx).
-
-## Contributing
-
-We welcome contributions from the community! Here's how you can help:
-
-1. **Report Issues** - Found a bug or have a feature request? Open an issue on GitHub
-2. **Submit Pull Requests** - Fork the repository, make your changes, and submit a PR
-3. **Improve Documentation** - Help us improve docs, tutorials, and examples
-
-Please ensure your contributions adhere to our coding standards and include appropriate tests.
+Sign up and start managing agents at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/).
 
-## License
+## Terms of Use
 
-This project is licensed under the Apache License 2.0 - see the [LICENSE](https://github.com/wso2/agent-manager/blob/main/LICENSE) file for details.
+By using WSO2 Agent Manager on the cloud, you agree to the [Terms of Use](https://wso2.com/cloud/agent-manager/terms-of-use).
```

</details>

### guides/amp-instrumentation

Main-line page `docs/guides/platform-administration/amp-instrumentation.mdx`; word F1 0.888.

<details><summary>Diff</summary>

```diff
--- main line: guides/amp-instrumentation.mdx
+++ Cloud: guides/amp-instrumentation.mdx
@@ -187,28 +187,4 @@ A couple of kinds work as a *kind* but don't have their full data card extracted
 - **Retriever documents.** The retrieved documents on a retriever span are not extracted in v1 (they aren't extracted for any instrumentation source today). The vectorDB chip, collection, and Top-K render; the document list doesn't.
 
-### Making traces filterable
-
-Auto-instrumentation (platform-hosted agents and `amp-instrument`) already records what the [trace filters](../concepts/observability.mdx#filter-traces) need. If your agent emits its own spans, this is what each filter reads:
-
-| Filter | What the observer reads |
-|---|---|
-| Status | On the root span: status `Error`, `error.type`, an error value in `gen_ai.tool.status`, or a numeric `http.status_code` of 400 or more |
-| Duration, Span count | The trace's start and end times and its number of spans |
-| Tokens | `gen_ai.usage.input_tokens` and `gen_ai.usage.output_tokens` (or `gen_ai.usage.prompt_tokens` and `gen_ai.usage.completion_tokens`). Read from the root span, then the root's first non-LLM child span, then summed over up to 50 LLM spans. |
-| Model | `gen_ai.response.model`, else `gen_ai.request.model`, on LLM spans |
-| Conversation ID | `gen_ai.conversation.id` (or `session.id` and similar session keys). Read from the root span, then the root's first non-LLM child span, then the LLM spans. |
-| Tool | The span name: `execute_tool <tool>`, or a name ending in `.tool`, `.tools`, `.function`, or `.functions` (for example `search_issues.tool`) |
-| Tool failed | Status `Error` on a tool span |
-| MCP server | `serverInfo.name` in the `traceloop.entity.output` of a span named `initialize.mcp` |
-
-The observer recognizes LLM spans by name: `chat`, `chat <model>`, or `<vendor>.chat`. It reads LLM spans only in traces with up to 100 spans, so in a larger trace, model, token, and conversation ID values found only on LLM spans are not seen. Tool filters read the span name, not `gen_ai.tool.name`.
-
-To make a manually instrumented agent's traces filterable:
-
-- Open one root span per request, with every other span inside it.
-- Set `gen_ai.conversation.id` and the token totals on the root span, and set its status to `Error` when the request fails.
-- Name LLM spans `chat <model>` and set the model and token attributes on them, as in [Setting up the exporter](#setting-up-the-exporter).
-- Name tool spans `execute_tool <tool>`, and set their status to `Error` when the call fails.
-
 ### Suppressing prompt and completion content
 
@@ -219,5 +195,5 @@ Prompt and completion content is captured by default. To suppress it, set `TRACE
 AMP's platform-injected auto-instrumentation covers Python (and Ballerina). A .NET agent joins AMP through the **external-agent path**: register it in the Console, then have it push spans to AMP's OTLP endpoint using the same transport and contract as above (`POST ${AMP_OTEL_ENDPOINT}/v1/traces`, header `x-amp-api-key`, `gen_ai.*` attributes). Nothing on the AMP side is .NET-specific — any process that emits contract-shaped spans to that endpoint renders in the Console and feeds evaluators.
 
-The runnable [`dotnet-agent`](https://github.com/wso2/agent-manager/tree/main/samples/dotnet-agent) sample is the worked example of everything below. [Sample Agents](../reference/sample-agents.mdx) lists the other six samples and which instrumentation path each one takes.
+The runnable [`dotnet-agent`](https://github.com/wso2/agent-manager/tree/main/samples/dotnet-agent) sample is the worked example of everything below.
 
 ### Where the `gen_ai.*` spans come from
@@ -289,6 +265,5 @@ These are the versions that ship with this AMP release:
 | AMP instrumentation version | Traceloop SDK (`traceloop-sdk`) | Supported Python versions | Init-container image tag |
 |---|---|---|---|
-| 0.4.2 (default) | 0.62.4 | 3.10, 3.11, 3.12, 3.13 | `ghcr.io/wso2/amp-python-instrumentation-provider:0.4.2-python<X.Y>` |
-| 0.4.1 | 0.62.3 | 3.10, 3.11, 3.12, 3.13 | `ghcr.io/wso2/amp-python-instrumentation-provider:0.4.1-python<X.Y>` |
+| 0.4.1 (default) | 0.62.3 | 3.10, 3.11, 3.12, 3.13 | `ghcr.io/wso2/amp-python-instrumentation-provider:0.4.1-python<X.Y>` |
 | 0.4.0 | 0.62.1 | 3.10, 3.11, 3.12, 3.13 | `ghcr.io/wso2/amp-python-instrumentation-provider:0.4.0-python<X.Y>` |
 | 0.3.0 | 0.61.0 | 3.10, 3.11, 3.12, 3.13 | `ghcr.io/wso2/amp-python-instrumentation-provider:0.3.0-python<X.Y>` |
@@ -302,31 +277,3 @@ The version set a given install actually accepts is assembled at runtime from th
 If you're picking a version in the create-agent form and see something that isn't in the table above, your platform admin added it. The pinned `traceloop-sdk` and supported Python versions for those entries live in the operator's chart values.
 
-Operators: see [Instrumentation Catalog](./instrumentation-catalog.mdx) for how to add a version, mirror images for air-gapped installs, and set the platform default.
-
-## Agent framework compatibility
-
-The zero-code path instruments a fixed set of agent frameworks, shipped inside the Traceloop SDK that each AMP-instrumentation version pins. **The framework set is the same across every AMP-instrumentation version and every supported Python version**, so you do not need to pick a particular version to get a particular framework.
-
-### Verified frameworks
-
-These are covered by the [instrumentation matrix test suite](https://github.com/wso2/agent-manager/tree/main/test/instrumentation-matrix), which runs on changes to the instrumentation packages and nightly, and asserts the exact span kinds listed. Each framework is exercised against every AMP-instrumentation version listed above:
-
-| Framework | Tested version | Spans produced | Known limitations |
-|---|---|---|---|
-| LangChain | 0.3.27 | LLM | — |
-| LangGraph | 0.2.74 | LLM, Tool | Instrumented via the LangChain package |
-| LlamaIndex | 0.12.0 | LLM, Embedding | Embedding spans omit the vendor attribute |
-| CrewAI | 1.1.0 | LLM, Agent, Task | No tool spans are emitted; 1.14.5 fails to install on instrumentation 0.3.0 (see below) |
-| OpenAI (direct SDK) | 2.38.0 | LLM | — |
-| Anthropic (direct SDK) | 0.45.0 | LLM | — |
-| Strands Agents (OpenAI) | 1.55.1 | Agent, Chain, LLM, Tool | Tested with `openai==2.38.0`; emission only (gateway and Observer delivery not covered) |
-
-:::warning CrewAI 1.14.5 does not install on AMP instrumentation 0.3.0
-`crewai 1.14.5` requires `opentelemetry-api >=1.34,<1.35`, while the `traceloop-sdk 0.61.0` that AMP instrumentation 0.3.0 pins requires `>=1.38,<2`. Installing both fails with `ResolutionImpossible` at install time rather than degrading at runtime.
-
-CrewAI 1.14 has not been tested on 0.4.0, 0.4.1, or 0.4.2, because the matrix pins CrewAI 1.1.0 for every version. All three resolve an `opentelemetry-api` above CrewAI 1.14.5's ceiling, so the same conflict is likely there, but it is unconfirmed. Stay on 1.1.x unless you have verified the combination yourself.
-:::
-
-OpenClaw is not in the matrix. It exports traces through its own plugin and is partially supported. See [Observe OpenClaw Agents](./observe-openclaw-agents.mdx).
-
-The canonical source for the verified-framework list is [`test/instrumentation-matrix/matrix.yaml`](https://github.com/wso2/agent-manager/blob/main/test/instrumentation-matrix/matrix.yaml); known limitations are tracked in [`FINDINGS.md`](https://github.com/wso2/agent-manager/blob/main/test/instrumentation-matrix/FINDINGS.md) alongside it.
+On Agent Manager Cloud the available instrumentation versions and the platform default are managed by WSO2.
```

</details>

### guides/authorize-agent-access-to-mcp-tools

Main-line page `docs/guides/agent-identity-and-access-management/authorize-agent-access-to-mcp-tools.mdx`; word F1 0.773.

<details><summary>Diff</summary>

```diff
--- main line: guides/authorize-agent-access-to-mcp-tools.mdx
+++ Cloud: guides/authorize-agent-access-to-mcp-tools.mdx
@@ -1,5 +1,5 @@
 # Authorize Agent Access to MCP Tools
 
-When you front an MCP server through the platform as an identity-secured MCP proxy, you decide which agents may invoke which tools. This guide walks through the full authorization workflow: you register the resource, define permissions over its tools, bundle those permissions into roles, and grant the roles to agents (or groups). The result is that two agents can hit the *same* proxy endpoint and get *different* capabilities.
+When you front an MCP server through the platform as an **identity-secured MCP proxy**, you decide which agents may invoke which tools. This guide walks through the full authorization workflow: you register the resource, define permissions over its tools, bundle those permissions into roles, and grant the roles to agents (or groups). The result is that two agents can hit the *same* proxy endpoint and get *different* capabilities.
 
 ## The model
@@ -10,5 +10,5 @@ Agent authorization is built from four pieces:
 | --- | --- |
 | **Resource** | The thing being accessed. Today this is an **MCP proxy**. Its handle becomes the prefix for every scope you define on it. |
-| **Permission (scope)** | An action on the resource, mapped to a set of the resource's tools. A scope is named `<proxy>:<action>` — e.g. `github:read`. |
+| **Permission (scope)** | An action on the resource, mapped to a set of the resource's tools. A scope is named `<proxy>:<action>` — e.g. `booking:read`. |
 | **Role** | A named bundle of scopes, defined in an environment. |
 | **Assignment** | A role granted to an **agent** or a **group**. |
@@ -16,13 +16,13 @@ Agent authorization is built from four pieces:
 An agent presents an access token, and the platform filters that token's scopes down to exactly the scopes of the agent's assigned roles **at mint time**. When the agent calls a tool through the gateway, per-tool authorization checks the token's scopes against the scope that covers the tool.
 
-The example below secures **GitHub's hosted MCP server** with two scopes and two roles, so you can follow along against a real upstream rather than a placeholder. The story is an IT helpdesk: one agent only reads the team's issue tracker to spot known problems, while a triage agent may also file and update issues.
+The example below secures a booking MCP server with two scopes and two roles:
 
-| | `github:read` | `github:write` |
+| | `booking:read` | `booking:write` |
 | --- | --- | --- |
-| **Tools** | `search_issues`, `list_issues`, `issue_read` | `issue_write`, `add_issue_comment` |
-| **`github-reader`** role | ✅ | — |
-| **`github-triager`** role | ✅ | ✅ |
+| **Tools** | `list_bookings`, `get_booking` | `create_booking`, `edit_booking`, `remove_booking` |
+| **`booking-reader`** role | ✅ | — |
+| **`booking-admin`** role | ✅ | ✅ |
 
-An agent assigned `github-reader` can search and read issues but not create them; an agent assigned `github-triager` can do both — through the same endpoint.
+An agent assigned `booking-reader` can list bookings but not create them; an agent assigned `booking-admin` can do both — through the same endpoint.
 
 :::info Platform-deployed vs. external agents
@@ -32,9 +32,9 @@ The authorization mechanism is identical for every agent. The only difference is
 ## Prerequisites
 
-- `amctl` installed and logged in against your control plane if you follow the `amctl` path (see [CLI Installation](./cli-installation.mdx) and [`amctl login`](../reference/cli/login.mdx)).
-- An AI Gateway registered and active for the environment you are configuring.
-- A **GitHub Personal Access Token**. Read access is enough for `github:read`; add issue write access only if you want to exercise `github:write`. Create one at [github.com/settings/tokens](https://github.com/settings/tokens).
+- `amctl` installed and logged in against your organization.
+- An active AI Gateway for the environment you are configuring. On Agent Manager Cloud this is provisioned for you.
+- A reachable upstream MCP server URL.
 
-This guide uses the [`amctl api`](../reference/cli/api.mdx) command to call the control plane directly, which makes every step precise and copy-pasteable. The examples use the `default` organization, `default` project, and `default` environment — substitute your own.
+This guide uses the `amctl api` command to call the control plane directly, which makes every step precise and copy-pasteable. The examples use the `default` organization, `default` project, and `default` environment — substitute your own.
 
 ---
@@ -44,45 +44,27 @@ This guide uses the [`amctl api`](../reference/cli/api.mdx) command to call the
 Register the upstream MCP server as an identity-secured MCP proxy. The proxy's `id` becomes the scope prefix and a resource server in the environment's Thunder identity provider, and — with a `context` — the gateway path.
 
-### In the Console
-
-1. Switch to the organization view and go to **MCP Servers** under **Resources**.
-2. Click **Register MCP Server** and give it the name `GitHub` and the context path `/github`.
-3. Add an endpoint with the **MCP Server Endpoint URL** `https://api.githubcopilot.com/mcp/`, then open **Advanced Configuration** and add the header `Authorization` with the value `Bearer <your-github-pat>`. Agent Manager discovers the server's tools as you add the endpoint. Now save the MCP proxy.
-4. Open the proxy's **Security** tab and set **Authentication** to **OAuth**. This is what turns on per-tool authorization — without it there are no scopes to define in Step 2.
-
-Full field reference: [Register an MCP Proxy](./register-mcp-proxy.mdx).
-
-### With amctl
-
 First discover the upstream server's tools:
 
 ```bash
-echo '{"url": "https://api.githubcopilot.com/mcp/",
-       "auth": {"type": "api-key", "header": "Authorization", "value": "Bearer <your-github-pat>"}}' \
+echo '{"url": "https://upstream.example.com/mcp"}' \
   | amctl api /orgs/default/mcp-proxies/fetch-server-info -X POST --input -
 ```
 
-Then create the proxy with identity security enabled. List only the tools this guide goes on to gate, rather than everything discovery returned — a tool present in `capabilities` but absent from every scope in Step 2 stays callable by any authenticated caller:
+Then create the proxy with identity security enabled, passing the discovered tools as the endpoint's capabilities:
 
 ```bash
 amctl api /orgs/default/mcp-proxies -X POST --input - <<'JSON'
 {
-  "id": "github",
-  "name": "GitHub MCP",
-  "description": "Proxy for GitHub's hosted MCP server",
+  "id": "booking",
+  "name": "Booking MCP",
+  "description": "Proxy for the upstream bookings MCP server",
   "version": "v1.0",
-  "context": "/github",
+  "context": "/booking",
   "mcpSpecVersion": "2025-06-18",
   "endpoints": [{
     "id": "primary",
     "name": "primary",
-    "upstream": {"main": {
-      "url": "https://api.githubcopilot.com/mcp/",
-      "auth": {"type": "api-key", "header": "Authorization", "value": "Bearer <your-github-pat>"}
-    }},
-    "capabilities": {"tools": [
-      "search_issues", "list_issues", "issue_read",
-      "issue_write", "add_issue_comment"
-    ]},
+    "upstream": {"main": {"url": "https://upstream.example.com/mcp"}},
+    "capabilities": {"tools": [ /* tools from fetch-server-info */ ]},
     "security": {"enabled": true, "identity": {"enabled": true}},
     "environments": [{"environmentUuid": "<environment-uuid>"}]
@@ -91,34 +73,23 @@ amctl api /orgs/default/mcp-proxies -X POST --input - <<'JSON'
 JSON
 ```
----
-
-## Step 2: Define permissions over the tools
-
-A **scope** on the proxy names an action and lists the tools it covers. Create one scope per capability level you want to grant. The scope string is `<proxy>:<action>`, so the steps below produce `github:read` and `github:write`.
-
-### In the Console
 
-On the proxy's **Security** tab, with **Authentication** set to **OAuth**, an **Authorization** section appears:
+You can also register a proxy through the Console — see [Register an MCP Proxy](./register-mcp-proxy.mdx) — but the rest of this guide uses the API for the parts that define authorization.
 
-1. Click **Create Scope**.
-2. Enter the action name — `read` — which becomes `github:read`.
-3. Select the tools it covers: `search_issues`, `list_issues` and `issue_read`.
-4. Optionally attach the scope to existing roles right here, which saves revisiting Step 3.
-5. Repeat for `write`, covering `issue_write` and `add_issue_comment`.
+---
 
-The **Tools** sub-tab shows a tool-to-scope table for the whole server, and the **Scopes** sub-tab lists what you've defined.
+## Step 2: Define permissions over the tools
 
-### With amctl
+A **scope** on the proxy names an action and lists the tools it covers. Create one scope per capability level you want to grant. The scope string is `<proxy>:<action>`, so the calls below produce `booking:read` and `booking:write`.
 
 ```bash
-# github:read — covers the read-only tools
-echo '{"action": "read", "description": "Search and read GitHub issues",
-       "tools": ["search_issues", "list_issues", "issue_read"]}' \
-  | amctl api /orgs/default/mcp-proxies/github/scopes -X POST --input -
-
-# github:write — covers the mutating tools
-echo '{"action": "write", "description": "File and update GitHub issues",
-       "tools": ["issue_write", "add_issue_comment"]}' \
-  | amctl api /orgs/default/mcp-proxies/github/scopes -X POST --input -
+# booking:read — covers the read-only tools
+echo '{"action": "read", "description": "Read-only booking access",
+       "tools": ["list_bookings", "get_booking"]}' \
+  | amctl api /orgs/default/mcp-proxies/booking/scopes -X POST --input -
+
+# booking:write — covers the mutating tools
+echo '{"action": "write", "description": "Create, edit and remove bookings",
+       "tools": ["create_booking", "edit_booking", "remove_booking"]}' \
+  | amctl api /orgs/default/mcp-proxies/booking/scopes -X POST --input -
 ```
 
@@ -127,8 +98,8 @@ A tool that is **not** covered by any scope has no authorization rule and is all
 :::
 
-List the scopes to confirm — the Console shows the same set on the **Scopes** sub-tab:
+List the scopes to confirm:
 
 ```bash
-amctl api /orgs/default/mcp-proxies/github/scopes
+amctl api /orgs/default/mcp-proxies/booking/scopes
 ```
 
@@ -139,26 +110,17 @@ amctl api /orgs/default/mcp-proxies/github/scopes
 Roles are defined per environment. Create a role with the set of scopes it should grant — the scopes must already exist (Step 2).
 
-### In the Console
-
-1. At the organization level, go to **Agent Identities → Roles**.
-2. Pick the environment you are configuring. Agent identity roles are per environment, so the same role name in development and production are different objects.
-3. Click **Create Role**, name it `github-reader`, and select the `github:read` scope.
-4. Repeat for `github-triager`, selecting both `github:read` and `github:write`.
-
-### With amctl
-
 ```bash
-# github-reader — read only
-echo '{"name": "github-reader", "description": "Read-only GitHub issues role",
-       "scopes": ["github:read"]}' \
+# booking-reader — read only
+echo '{"name": "booking-reader", "description": "Read-only booking role",
+       "scopes": ["booking:read"]}' \
   | amctl api /orgs/default/environments/default/agent-identities/roles -X POST --input -
 
-# github-triager — read and write
-echo '{"name": "github-triager", "description": "Read plus file/update issues",
-       "scopes": ["github:read", "github:write"]}' \
+# booking-admin — read and write
+echo '{"name": "booking-admin", "description": "Full booking access role",
+       "scopes": ["booking:read", "booking:write"]}' \
   | amctl api /orgs/default/environments/default/agent-identities/roles -X POST --input -
 ```
 
-Fetch the roles back to get each role's ID, which you'll need to assign it (the Console does this lookup for you):
+Fetch the roles back to get each role's ID, which you'll need to assign it:
 
 ```bash
@@ -170,14 +132,5 @@ amctl api /orgs/default/environments/default/agent-identities/roles
 ## Step 4: Assign the role to an agent or group
 
-Assignments grant a role to a principal — `agent` for a single agent identity, or `group` to grant every member of a group at once.
-
-### In the Console
-
-1. Go to **Roles** in the **Agent Identities** section and open `github-reader`.
-2. Use the **agent** tabs to pick the agents, or the groups, that should hold the role, then save.
-
-**Agent ID → Agents** lists the agent identities available in the selected environment if you need to confirm a name first, and **Agent ID → Groups** is where you manage group membership.
-
-### With amctl
+Assignments grant a role to a principal. Each assignment names the principal's ID and its `type` — `agent` to grant a single agent identity, or `group` to grant every member of a group at once.
 
 First resolve the agent's identity ID (`thunderAgentId`):
@@ -190,5 +143,5 @@ Then add the assignment, using the role ID from Step 3:
 
 ```bash
-# Grant github-reader to an agent
+# Grant booking-reader to an agent
 echo '{"assignments": [{"id": "<thunder-agent-id>", "type": "agent"}]}' \
   | amctl api /orgs/default/environments/default/agent-identities/roles/<role-id>/assignments/add -X POST --input -
@@ -214,10 +167,10 @@ amctl api /orgs/default/environments/default/agent-identities/roles/<role-id>/as
 Once a role is assigned, the platform enforces it automatically:
 
-1. The agent obtains an access token. Its scopes are **filtered to the scopes of its assigned roles at mint time**. A `github-reader` agent that requests `github:read github:write` receives a token carrying only `github:read`.
-2. The agent calls a tool through the gateway endpoint (`/github/mcp`).
+1. The agent obtains an access token. Its scopes are **filtered to the scopes of its assigned roles at mint time** — a `booking-reader` agent that requests `booking:read booking:write` receives a token carrying only `booking:read`.
+2. The agent calls a tool through the gateway endpoint (`/booking/mcp`).
 3. The gateway authenticates the token, then authorizes the specific tool against the token's scopes:
-   - `github-reader` calling `search_issues` → **allowed** (`github:read` covers it).
-   - `github-reader` calling `issue_write` → **denied** (`github:write` required, not granted).
-   - `github-triager` calling either → **allowed**.
+   - `booking-reader` calling `list_bookings` → **allowed** (`booking:read` covers it).
+   - `booking-reader` calling `create_booking` → **denied** (`booking:write` required, not granted).
+   - `booking-admin` calling either → **allowed**.
 
 Changing who can do what is now a matter of editing scopes and role assignments — the agents themselves do not change.
@@ -225,5 +178,5 @@ Changing who can do what is now a matter of editing scopes and role assignments
 ## Next steps
 
-- [Authorization](../reference/authorization.mdx) — the platform-wide scope and role model these agent scopes plug into.
+- [AgentID](../concepts/agentid.mdx) — the identity each agent is issued, and how these scopes attach to it.
 - [Register an MCP Proxy](./register-mcp-proxy.mdx) — the full proxy registration reference, including the Console flow.
 - [Configure Agent MCP Proxies](./configure-agent-mcp-proxies.mdx) — attach a proxy to an agent so it can call the tools.
```

</details>

### guides/configure-agent-llm-configuration

Main-line page `docs/guides/platform-administration/configure-agent-llm-configuration.mdx`; word F1 0.994.

<details><summary>Diff</summary>

```diff
--- main line: guides/configure-agent-llm-configuration.mdx
+++ Cloud: guides/configure-agent-llm-configuration.mdx
@@ -120,5 +120,5 @@ The **Setup Agent** panel provides a **Zero-code Instrumentation Guide** to conn
 3. **Set environment variables**:
    ```bash
-   export AMP_OTEL_ENDPOINT="http://default-default.gateway.localhost:19080/otel"
+   export AMP_OTEL_ENDPOINT="<INSTRUMENTATION_URL>"
    export AMP_AGENT_API_KEY="<your-generated-token>"
    ```
@@ -150,5 +150,5 @@ The **Setup Agent** panel provides a **Zero-code Instrumentation Guide** to conn
 5. **Set environment variables**:
    ```bash
-   export BAL_CONFIG_VAR_BALLERINAX_AMP_OTELENDPOINT="http://default-default.gateway.localhost:19080/otel"
+   export BAL_CONFIG_VAR_BALLERINAX_AMP_OTELENDPOINT="<INSTRUMENTATION_URL>"
    export BAL_CONFIG_VAR_BALLERINAX_AMP_APIKEY="<your-generated-token>"
    ```
```

</details>

### guides/configure-agent-mcp-proxies

Main-line page `docs/guides/agent-identity-and-access-management/configure-agent-mcp-proxies.mdx`; word F1 0.863.

<details><summary>Diff</summary>

```diff
--- main line: guides/configure-agent-mcp-proxies.mdx
+++ Cloud: guides/configure-agent-mcp-proxies.mdx
@@ -5,14 +5,4 @@ Agents can be configured to use one or more [MCP Proxies](./register-mcp-proxy.m
 The agent does not embed the proxy. It references it, and the platform resolves the proxy's endpoint for the agent's target environment at deploy time. Because the org-level proxy owns its per-environment gateway artifacts, changing the proxy does not redeploy the agent automatically — the agent picks up any change on its next deployment.
 
-:::tip
-The API key described in this guide **authenticates** the agent: it proves the caller
-is allowed to reach the proxy at all. It says nothing about *which* tools that agent
-may invoke — any agent holding a valid key can call every tool the endpoint exposes.
-
-When you need that granularity(controling which agent access which tool). See
-[Authorize Agent Access to MCP Tools](./authorize-agent-access-to-mcp-tools.mdx),
-which covers per-tool **authorization** on top of authentication.
-:::
-
 ## Prerequisites
 
@@ -100,48 +90,4 @@ The variable names in the snippet match whatever you set in Step 3.
 > Renaming the variables here only changes their names — *"These variable names are injected into the agent at runtime with environment-specific values. Rename them here if your code already uses different names, then save."*
 
-#### OAuth (AgentID)-Secured Proxies
-
-If the proxy's Security tab is set to **OAuth** instead of **API Key**, the panel shows an **AgentID Variables** section instead of an API key, and the Integration Guide snippet mints a token instead of reading one:
-
-```python
-import os
-from typing import Any
-import requests
-from langchain_mcp_adapters.client import MultiServerMCPClient
-
-mcp_server_url = os.environ.get("MY_PROXY_URL", "").strip()
-
-client_id = os.environ["AMP_AGENTID_CLIENT_ID"]
-client_secret = os.environ["AMP_AGENTID_CLIENT_SECRET"]
-token_endpoint = os.environ["AMP_AGENTID_TOKEN_ENDPOINT"]
-scopes = os.environ["AMP_AGENTID_SCOPES"]
-
-token_response = requests.post(
-    token_endpoint,
-    auth=(client_id, client_secret),
-    data={
-        "grant_type": "client_credentials",
-        "scope": scopes,
-        "resource": mcp_server_url,  # scopes the token to this proxy (RFC 8707)
-    },
-    timeout=30,
-)
-token_response.raise_for_status()
-access_token = token_response.json()["access_token"]
-
-server_configs: dict[str, dict[str, Any]] = {
-    "mcp_server": {
-        "url": mcp_server_url,
-        "transport": "streamable_http",
-        "headers": {"Authorization": f"Bearer {access_token}"},
-    }
-} if mcp_server_url else {}
-
-mcp_client = MultiServerMCPClient(server_configs)
-tools = await mcp_client.get_tools()
-```
-
-The `AMP_AGENTID_*` variable names are fixed and not renameable. See [Use AgentID in a Platform-Hosted Agent](./use-agentid-in-platform-hosted-agents.mdx) for how these are provisioned and injected. For an OAuth-secured proxy on an **External** agent, see [Configuring an MCP Proxy for an External Agent](#configuring-an-mcp-proxy-for-an-external-agent) below.
-
 ---
 
@@ -187,33 +133,4 @@ curl -N <endpoint-url> \
 Configure your agent's MCP client using the Endpoint URL and pass the API Key in the configured header on every request.
 
-#### OAuth (AgentID)-Secured Proxies
-
-If the proxy's Security tab is set to **OAuth** instead of **API Key**, Step 2 above doesn't apply — there's no API key to manage. The **Connect to MCP Server** panel shows different fields instead:
-
-| Field | Description |
-|---|---|
-| **MCP URL** | The gateway invoke URL for this MCP proxy in the selected environment |
-| **Client ID** / **Client Secret** | This agent's OAuth 2.0 credentials for this environment (the secret is shown once, right after it's generated or rotated) |
-| **Issuer URL** | This environment's ThunderID issuer, useful for verifying tokens |
-| **Token Endpoint** | The `/oauth2/token` endpoint to request a token from |
-| **JWKS Endpoint** | This environment's JSON Web Key Set, for verifying token signatures |
-| **Available Scopes** | The scopes to request when minting a token |
-
-Copy these values into your external agent's own environment (there is no automatic injection, since the platform doesn't run this agent's process). Mint a token with the `client_credentials` grant, passing the **MCP URL** as the `resource` parameter (RFC 8707) so the token is scoped to this specific proxy, then call the MCP URL with it as a Bearer token:
-
-```bash
-TOKEN=$(curl -s -X POST "<token-endpoint>" \
-  -u "<client-id>:<client-secret>" \
-  -d "grant_type=client_credentials" \
-  -d "scope=<scopes>" \
-  -d "resource=<mcp-url>" \
-  | jq -r .access_token)
-
-curl -N <mcp-url> \
-  --header "Authorization: Bearer $TOKEN"
-```
-
-Rotate credentials from the **Agent ID** page (top-right on the agent's Overview page) if a secret is lost or needs to be regenerated.
-
 ---
 
@@ -273,3 +190,2 @@ If you have confirmed the proxy is deployed to the environment and the connectio
 - The external agent API Key is displayed only right after it is generated or rotated. If lost, rotate the key from the tool configuration's API key section (per environment) to obtain a new value.
 - A single proxy attached from the Configure page maps to every environment in the agent's pipeline; the proxy supplies each environment's endpoint. To use different proxies per environment, attach them during agent creation.
-- An API key controls **whether** an agent may call the proxy, not **which tools** it may call. For per-tool control, use an identity-secured proxy with scopes and roles — see [Authorize Agent Access to MCP Tools](./authorize-agent-access-to-mcp-tools.mdx).
```

</details>

### guides/custom-evaluators

Main-line page `docs/guides/evaluation-and-observability/custom-evaluators.mdx`; word F1 0.986.

<details><summary>Diff</summary>

```diff
--- main line: guides/custom-evaluators.mdx
+++ Cloud: guides/custom-evaluators.mdx
@@ -8,5 +8,5 @@ This guide walks you through creating custom evaluators in the AMP Console. Cust
 ## Prerequisites
 
-- A running AMP instance (see [Quick Start](../get-started/quick-start.mdx))
+- An Agent Manager Cloud account (sign up at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/))
 - An agent registered in AMP with an active environment
 - Familiarity with [evaluation concepts](../concepts/evaluation.mdx), especially evaluator types and evaluation levels
```

</details>

### guides/deploy-an-a2a-agent

Main-line page `docs/guides/deploy-an-a2a-agent.mdx`; word F1 0.857.

<details><summary>Diff</summary>

```diff
--- main line: guides/deploy-an-a2a-agent.mdx
+++ Cloud: guides/deploy-an-a2a-agent.mdx
@@ -1,5 +1,2 @@
-import Tabs from '@theme/Tabs';
-import TabItem from '@theme/TabItem';
-
 # Deploy an A2A Agent
 
@@ -26,12 +23,8 @@ Clients reach the agent only through the gateway, so the gateway's CORS and auth
 - An agent that serves the A2A protocol on a single port, with JSON-RPC under `/rpc`, HTTP+JSON under `/rest`, and its card at `/.well-known/agent-card.json`. The [A2A Notes Agent sample](../tutorials/deploy-the-a2a-notes-agent-sample.mdx) is a working example built on the `a2a-sdk` Python package.
 - The agent's source in a GitHub repository.
-- A project to create the agent in.
-- To use the CLI: `amctl` installed and logged in. See [CLI Installation](./cli-installation.mdx).
+- An Agent Manager Cloud account. Sign up at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/) if you don't have one yet.
 
 ## Step 1: Create the Agent
 
-<Tabs groupId="am-client">
-<TabItem value="console" label="Console" default>
-
 1. Open your project and click **Add Agent**.
 2. Choose **Platform-Hosted Agent**, then **Source Code** as the source type.
@@ -43,36 +36,4 @@ Clients reach the agent only through the gateway, so the gateway's CORS and auth
 There is no **OpenAPI Spec Path** or **Base Path** field for an A2A agent. It needs only a port.
 
-</TabItem>
-<TabItem value="cli" label="amctl">
-
-Pass `--subtype a2a-agent` and the port the agent listens on:
-
-```bash
-amctl agent create <agent-name> \
-  --display-name "<display-name>" \
-  --subtype a2a-agent \
-  --port <port> \
-  --repo-url <repository-url> \
-  --repo-branch main \
-  --repo-path <path-to-agent> \
-  --build-type buildpack \
-  --language python \
-  --language-version 3.11 \
-  --run-command "python main.py"
-```
-
-`--port` falls back to `8000` when you omit it, so always pass the port your A2A server listens on. `--openapi-spec` is rejected for `a2a-agent`. Then build and deploy:
-
-```bash
-amctl agent build create <agent-name>
-amctl agent deploy <agent-name>
-amctl agent status <agent-name>
-```
-
-See [`amctl agent`](../reference/cli/agent.mdx) for every flag.
-
-</TabItem>
-</Tabs>
-
 :::note The A2A choice is permanent
 You can switch an agent between **Chat Agent** and **Custom API Agent** later, but not into or out of **A2A Agent**. To change an A2A agent into another type, create a new agent.
@@ -113,16 +74,5 @@ There is no **Request Timeout** section for an A2A agent. A timeout would cut of
 Saving these settings republishes the agent to the gateway. Promoting the agent to another environment publishes it there too.
 
-## Step 3: Check the Agent Card
-
-Once the agent is deployed, Agent Manager reads its card in each environment and shows it in the Console.
-
-1. Open the agent. In the left sidebar, under **Agent Lifecycle**, click **Configure**.
-2. Click the **A2A** tab, then select the environment's tab.
-
-The **Agent Card** panel shows the card's name, version, **Interfaces**, and **Skills**, with the time it was fetched. Click **View JSON** to see the whole card. The agent's overview shows a summary of the same card in its **Agent Card** section.
-
-The card shows **Pending** until Agent Manager has read it. If it shows **Failed**, fix the cause shown with it, then click **Refetch**. Click **Refetch** as well after you change the card the agent serves without redeploying it.
-
-## Step 4: Call the Agent
+## Step 3: Call the Agent
 
 The **Try It** page cannot call an A2A agent. It shows "Testing isn't available for A2A agents yet". Use an A2A client or `curl` instead.
@@ -157,5 +107,4 @@ An A2A client can instead fetch the card from `<invoke-url>/.well-known/agent-ca
 
 - [Deploy the A2A Notes Agent Sample](../tutorials/deploy-the-a2a-notes-agent-sample.mdx): deploy a working A2A agent end to end.
-- [Register an External A2A Agent](./register-an-external-a2a-agent.mdx): bring an A2A agent that runs outside Agent Manager, and route it through the gateway.
 - [Configure CORS for Agent Endpoints](./configure-cors-for-agent-endpoints.mdx)
 - [Secure Agent Endpoints with API Keys](./secure-agent-endpoints-with-api-keys.mdx)
```

</details>

### guides/environment-management

Main-line page `docs/guides/platform-administration/environment-management.mdx`; word F1 0.637.

<details><summary>Diff</summary>

```diff
--- main line: guides/environment-management.mdx
+++ Cloud: guides/environment-management.mdx
@@ -11,7 +11,5 @@ Both environments and deployment pipelines live under the **Infrastructure** sec
 ## Prerequisites
 
-- Admin access to the WSO2 Agent Manager Console.
-- A terminal with `kubectl` and `helm` configured against your cluster (environments are provisioned and removed by a script that installs/uninstalls an API Platform Gateway via Helm).
-- At least one [AI Gateway](../concepts/gateway.mdx) active. The installer registers one per environment.
+- access to the WSO2 Agent Manager Cloud Console with the relvant permission to create new enviroments.
 
 ---
@@ -29,6 +27,4 @@ Both environments and deployment pipelines live under the **Infrastructure** sec
 ### Create an environment
 
-Environments are provisioned by a script that creates the environment in Agent Manager and installs its API Platform Gateway via Helm. The Console builds the command for you.
-
 1. Click **Create Environment**.
 2. Fill in the environment details.
@@ -36,77 +32,27 @@ Environments are provisioned by a script that creates the environment in Agent M
    | Field | Description | Example |
    |---|---|---|
-   | **Display Name** | Human-readable name shown throughout the Console. | `Production` |
-   | **Identity Service Handle** | Optional unique DNS label for this environment's ThunderID URL. Use 3–63 lowercase letters, digits, or hyphens; leave it blank to let Agent Manager generate an unguessable handle. | `x7f2q9kzab` |
-   | **Isolation Tier** | Container runtime isolation for agents deployed to this environment. The dropdown lists three sandboxing tiers of increasing strength — `Sandboxing T1 (runc)` (default), `Sandboxing T2 (gVisor)`, and `Sandboxing T3 (Kata Containers)`. Stronger tiers need a dedicated node set up first; see [Isolation tiers](#isolation-tiers) below. | `Sandboxing T1 (runc)` |
-   | **Production environment** | Mark this environment as production. Production environments are typically the last stage of a pipeline. | — |
-
-3. Copy the generated command using the copy icon. Your access token is substituted into the command automatically when you copy.
-4. Run the command from a terminal that has `kubectl` and `helm` configured against your cluster.
-
-   The script creates the environment in Agent Manager and provisions an API Platform Gateway for that environment via Helm.
-
-   > The script is idempotent — it is safe to re-run. Once it completes, the new environment appears in the list.
-
-### Isolation tiers
-
-Every environment has an **isolation tier** that decides which container runtime its agents run under. The tier is chosen at environment creation time and cannot be changed afterwards.
-
-The Console presents the tiers as three sandboxing levels of increasing strength, each marked by its own shield icon. The environment list shows the tier as a **Sandboxing T1**–**T3** shield chip, and on an agent's Deploy and Overview pages (and in a pipeline's promotion chain) a shield icon next to the environment name identifies its tier — hover over it to see the tier and runtime, e.g. *Sandboxing Tier 2 — gVisor*.
-
-| Console label | Tier value | Runtime | Isolation | Requirements |
-|------|------|---------|-----------|--------------|
-| **Sandboxing T1** (default) | `runc` | Standard container runtime | Sandboxed pod, shared host kernel | None — works everywhere |
-| **Sandboxing T2** | `gvisor` | gVisor (`runsc`) | Userspace kernel intercepts syscalls | A dedicated x86_64 node — see the [gVisor guide](./isolation-tiers/gvisor.mdx) |
-| **Sandboxing T3** | `kata` | Kata Containers (`kata-qemu`) | Per-agent VM with its own guest kernel | A dedicated node with KVM — see the [Kata guide](./isolation-tiers/kata.mdx) |
-
-To create an environment with a stronger tier, set up the node first (per the guides above), then pick the tier from the **Isolation Tier** dropdown in the **Create Environment** drawer. The generated command automatically includes the matching `ISOLATION_TIER` variable — for `runc` (the default) no variable is added. Selecting gVisor or Kata also shows a warning with a link to the corresponding node setup guide.
-
-If you script environment creation directly instead of using the Console, set the variable yourself:
-
-```bash
-ISOLATION_TIER=gvisor \
-  ENV_NAME=... DISPLAY_NAME=... AGENT_MANAGER_TOKEN=... \
-  bash add-environment.sh
-```
-
-Agents deployed or promoted to that environment automatically run under the tier's runtime — no agent-side changes are needed.
+   | **Display Name** *(required)* | Human-readable name shown throughout the Console. | `Production` |
+   | **Name** | The resource name used by the API. Generated automatically from the display name and guaranteed unique. | `production` |
+   | **Production environment** | Mark this environment as production. Production environments are typically the last stage of a pipeline, and deploying to one requires a [separate permission](../concepts/organization.mdx). | — |
 
-### Gateway topology
+3. Click **Create**.
 
-Every environment gets an API Platform Gateway. Its **topology** decides whether one gateway handles both directions of traffic, or two gateways split the roles — an *ingress* gateway for traffic arriving at the agents deployed in the environment, and an *egress* gateway for the calls those agents make out to LLMs, MCP servers, and other APIs.
+Agent Manager provisions the environment and installs its API Platform Gateway for
+you. Once created, the new environment appears in the list.
 
-| Topology | Helm releases installed | Namespaces | Registered gateway type |
-|---|---|---|---|
-| `single` (default) | `api-platform-<org>-<env>` | `<org>-<env>` | `BOTH` |
-| `split` | `api-platform-<org>-<env>` and `api-platform-<org>-<env>-egress` | `<org>-<env>` and `<org>-<env>-egress` | `INGRESS` and `EGRESS` |
-
-In split topology each release is a complete gateway of its own — its own `APIGateway` resource, its own runtime, its own routing hostname (`<env>-<org>.gateway.localhost` for ingress, `<env>-<org>-egress.gateway.localhost` for egress) — and each registers with Agent Manager separately, with its own cluster-local runtime URL.
-
-A gateway's type is fixed when it first registers and cannot be changed afterward, so an environment's topology cannot be switched in place. To move an existing environment to split topology, delete it and create it again.
-
-:::warning
-Split topology shortens the maximum `ENV_NAME` by 7 characters, to leave room for the `-egress` suffix on the second release's Kubernetes resource names. The limit is `22 - len(ORG_NAME)` characters, minus a further 7 in split topology — for the default organization `default` that leaves **8 characters**, so `ENV_NAME=production` is rejected. Use a shorter name such as `prod`.
-
-The name the Console generates for you is not bounded by the split limit, so shorten it if you are creating a split environment.
+:::note
+The environment also gets its own identity service, which issues
+[AgentID](../concepts/agentid.mdx) credentials to every agent deployed there. It is
+provisioned and operated by WSO2 — there is nothing to install or configure.
 :::
 
-The **Create Environment** drawer has no topology option, and the command it generates always creates a single-topology environment. If you script environment creation directly instead of using the Console, set the variable yourself:
-
-```bash
-GATEWAY_TOPOLOGY=split \
-  ENV_NAME=... DISPLAY_NAME=... AGENT_MANAGER_TOKEN=... \
-  bash add-environment.sh
-```
-
-Deletion needs no equivalent flag: the delete command detects the egress release and namespace and removes them along with the ingress gateway, and does nothing extra for a single-topology environment.
-
 ### Delete an environment
 
 1. On the Environments page, open the **Delete** action for the environment you want to remove.
-2. Copy the generated command and run it from a terminal configured against your cluster (again with `kubectl` and `helm` configured).
+2. Confirm in the dialog.
 
-   The script uninstalls the environment's API Platform Gateway Helm release and then deletes the environment in Agent Manager.
+   Agent Manager removes the environment and the API Platform Gateway it provisioned for it.
 
-   > **Warning:** Deleting an environment is permanent and cannot be undone. Any agent deployed to the environment will no longer be reachable, and the deployment will be permanently deleted. Every agent's settings for the environment (CORS, endpoint authentication, and instrumentation settings) are deleted too, so an environment you create again with the same name starts from the defaults.
+   > **Warning:** Deleting an environment is permanent and cannot be undone. Any agent deployed to the environment will no longer be reachable, and the deployment will be permanently deleted.
 
 :::note
@@ -116,46 +62,17 @@ An environment cannot be deleted while it is still referenced by a deployment pi
 ### Access the Environment ThunderID Console
 
-Creating an environment does more than register it in Agent Manager. The same command also
-provisions a dedicated ThunderID instance for that environment, which is what issues
-[AgentID](../concepts/agentid.mdx) credentials to every agent deployed there.
-
-The command's terminal output ends with the console details for the new instance:
-
-```text
-━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
-  Thunder ID Console - production
-━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
-  URL:      http://x7f2q9kzab.amp.localhost:8080/console
-  Username: admin
-  Password: <a freshly generated password>
-━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
-```
-
-Save the password before you close the terminal. It is generated once when the environment is
-created, and is not displayed again.
-
-| Field | Where it comes from |
-|---|---|
-| **URL** | `http://<handle>.<base domain>:8080/console` for a local installation, or an `https://` address on a VM or cluster with TLS enabled. `<handle>` is the unguessable handle registered for this environment (user-chosen or server-generated). |
-| **Username** | Always `admin`, scoped to this environment's ThunderID instance only. |
-| **Password** | Randomly generated the first time the environment is provisioned, then reused on every re-run of the same command. |
-
-:::tip
-If you lose the password, you do not need to recreate the environment. It is stored in a
-Kubernetes secret named `amp-thunder-<org>-<env>-admin-credentials`, in the namespace of the
-same name, and can be read again with:
-
-```bash
-kubectl get secret amp-thunder-<org>-<env>-admin-credentials \
-  -n amp-thunder-<org>-<env> \
-  -o jsonpath="{.data.password}" | base64 -d
-```
-:::
+Each environment has its own ThunderID instance, and that instance is what issues
+[AgentID](../concepts/agentid.mdx) credentials to every agent deployed in the
+environment. A few tasks are done in its console rather than in Agent Manager —
+creating an OAuth application for an externally-hosted agent, for example, or
+looking up an agent's application by name.
+
+On Agent Manager Cloud the instance is provisioned and operated by WSO2. The console
+URL and its administrator credentials are issued to your organization along with the
+environment; ask your WSO2 administrator if you do not have them.
 
-Log in to this console to inspect the environment's ThunderID instance directly, for example to
-look up an agent's OAuth application by name. Day-to-day AgentID operations such as
-provisioning, viewing, rotating, and revoking a credential are done through Agent Manager
-instead, as described in [AgentID](../concepts/agentid.mdx), so you do not need to work in this
-console for routine tasks.
+Day-to-day AgentID work — provisioning, viewing, rotating, and revoking a
+credential — is done through Agent Manager instead, as described in
+[AgentID](../concepts/agentid.mdx), so you should rarely need this console.
 
 ---
```

</details>

### guides/evaluation-monitors

Main-line page `docs/guides/evaluation-and-observability/evaluation-monitors.mdx`; word F1 0.988.

<details><summary>Diff</summary>

```diff
--- main line: guides/evaluation-monitors.mdx
+++ Cloud: guides/evaluation-monitors.mdx
@@ -5,5 +5,5 @@ This guide walks you through creating an evaluation monitor, viewing results, an
 ## Prerequisites
 
-- A running AMP instance (see [Quick Start](../get-started/quick-start.mdx))
+- An Agent Manager Cloud account (sign up at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/))
 - An agent registered in AMP with an active environment
 - Agent traces being collected (see [Observe Your First Agent](../tutorials/observe-first-agent.mdx))
```

</details>

### guides/register-llm-service-provider

Main-line page `docs/guides/platform-administration/register-llm-service-provider.mdx`; word F1 0.969.

<details><summary>Diff</summary>

```diff
--- main line: guides/register-llm-service-provider.mdx
+++ Cloud: guides/register-llm-service-provider.mdx
@@ -4,5 +4,5 @@ LLM Service Providers are organization-level resources that represent connection
 
 :::tip Prefer the CLI?
-You can also create, list, and delete providers from the command line — see [`amctl llm-provider`](../reference/cli/llm-provider.mdx).
+You can also create, list, and delete providers from the command line with `amctl llm-provider`.
 :::
 
@@ -10,5 +10,5 @@ You can also create, list, and delete providers from the command line — see [`
 
 - Admin access to the WSO2 Agent Manager Console
-- At least one [AI Gateway](../concepts/gateway.mdx) active. The installer registers one per environment; gateways are not created from the console.
+- An active AI Gateway. On Agent Manager Cloud this is provisioned for you — no setup required.
 - API credentials for the target LLM provider (e.g., an OpenAI API key)
 
@@ -17,5 +17,5 @@ You can also create, list, and delete providers from the command line — see [`
 ## Step 1: Navigate to LLM Service Providers
 
-1. Log in to the WSO2 Agent Manager Console (`http://console.amp.localhost:8080`).
+1. Log in to the WSO2 Agent Manager Console at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/).
 2. Go to the Organization level by closing the projects section from the top navigation.
 3. In the left sidebar, click **LLM Service Providers** under the **RESOURCES** section.
```

</details>

### guides/register-mcp-proxy

Main-line page `docs/guides/platform-administration/register-mcp-proxy.mdx`; word F1 0.992.

<details><summary>Diff</summary>

```diff
--- main line: guides/register-mcp-proxy.mdx
+++ Cloud: guides/register-mcp-proxy.mdx
@@ -28,5 +28,5 @@ Agents do not embed the proxy — they **reference** it. Each agent resolves the
 
 - Admin access to the WSO2 Agent Manager Console
-- At least one [AI Gateway](../concepts/gateway.mdx) active for the environments you want to configure. The installer registers one per environment.
+- An active [AI Gateway](../concepts/gateway.mdx) for the environments you want to configure. On Agent Manager Cloud these are provisioned for you.
 - A reachable upstream MCP server endpoint for each environment (e.g., `https://api.example.com/mcp`)
 - Any credential the upstream MCP server requires (e.g., an API key passed in an HTTP header)
@@ -36,5 +36,5 @@ Agents do not embed the proxy — they **reference** it. Each agent resolves the
 ## Step 1: Navigate to MCP Proxies
 
-1. Log in to the WSO2 Agent Manager Console (`http://console.amp.localhost:8080`).
+1. Log in to the WSO2 Agent Manager Console at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/).
 2. Go to the Organization level by closing the projects section from the top navigation.
 3. In the left sidebar, click **MCP Proxies** under the **Resources** section.
```

</details>

### guides/secure-agent-endpoints-with-api-keys

Main-line page `docs/guides/securing-agent-endpoints/secure-agent-endpoints-with-api-keys.mdx`; word F1 0.971.

<details><summary>Diff</summary>

```diff
--- main line: guides/secure-agent-endpoints-with-api-keys.mdx
+++ Cloud: guides/secure-agent-endpoints-with-api-keys.mdx
@@ -5,6 +5,4 @@ API key security protects platform-hosted API agent endpoints at the gateway. Wh
 API key security is enabled by default for API agents. You can turn it off or on when deploying the agent, and you can create and revoke keys from **Credentials** under the **SECURITY** section in the agent sidebar.
 
-An externally-hosted A2A agent can use agent API keys too, once it is routed through the environment's gateway. See [Register an External A2A Agent](./register-an-external-a2a-agent.mdx).
-
 ## Prerequisites
 
```

</details>

### guides/secure-agents-with-jwt-authentication

Main-line page `docs/guides/securing-agent-endpoints/secure-agents-with-jwt-authentication.mdx`; word F1 0.984.

<details><summary>Diff</summary>

```diff
--- main line: guides/secure-agents-with-jwt-authentication.mdx
+++ Cloud: guides/secure-agents-with-jwt-authentication.mdx
@@ -4,5 +4,5 @@ JWT authentication protects platform-hosted API agent endpoints at the gateway.
 callers must send a valid JWT, by default in the `Authorization: Bearer <token>` header. The
 gateway validates the token's issuer, signature, and expiry against the
-[identity providers](./configure-identity-providers-at-the-gateway.mdx) you select for the
+identity providers you select for the
 agent, and its `aud` claim if you configure audiences.
 
@@ -13,5 +13,5 @@ an agent uses one or the other, not both.
 
 - A platform-hosted API agent created in a project.
-- At least one [identity provider configured](./configure-identity-providers-at-the-gateway.mdx) on the
+- At least one identity provider configured on the
   environment's gateway.
 
@@ -90,5 +90,5 @@ JWT authentication and API key security cannot be active at the same time.
 - JWT authentication applies to platform-hosted API agents.
 - Accepted issuers and audiences come from the
-  [identity providers configured on the gateway](./configure-identity-providers-at-the-gateway.mdx).
+  identity providers configured on the gateway.
 - An agent uses one authentication method at a time — JWT authentication or API key, not both.
 - Authentication will be enforced by the gateway based on issuer and audience claims.
```

</details>

### guides/use-agentid-in-platform-hosted-agents

Main-line page `docs/guides/agent-identity-and-access-management/use-agentid-in-platform-hosted-agents.mdx`; word F1 0.912.

<details><summary>Diff</summary>

```diff
--- main line: guides/use-agentid-in-platform-hosted-agents.mdx
+++ Cloud: guides/use-agentid-in-platform-hosted-agents.mdx
@@ -74,14 +74,8 @@ def agent_identity_ready() -> bool:
 ## Step 2: Mint and Cache a Token
 
-Request a token using the `client_credentials` grant, passing the MCP tool's own URL as the
-`resource` parameter (RFC 8707, OAuth 2.0 target-resource indication). ThunderID scopes the
-minted token to that one resource, so a token minted for one MCP tool is not valid for another,
-if your agent calls more than one tool, cache one token **per resource**, not a single global
-token.
-
-Tokens are valid for about an hour, so cache each one instead of requesting a new one on every
-call. If your agent handles requests concurrently, coalesce refreshes per resource too: without
-it, every concurrent caller sees that resource's cache expired at the same moment and each fires
-its own token request.
+Request a token using the `client_credentials` grant. Tokens are valid for about an hour, so
+mint one and cache it instead of requesting a new token on every call. If your agent handles
+requests concurrently, coalesce refreshes too: without it, every concurrent caller sees the
+cache expired at the same moment and each fires its own token request.
 
 ```python
@@ -90,13 +84,16 @@ import time
 import requests
 
-_cached_tokens: dict[str, str] = {}  # resource URL -> access token
-_cached_expiries: dict[str, float] = {}  # resource URL -> expiry (epoch seconds)
+_cached_token = None
+_cached_token_expiry = 0
 _cache_lock = threading.Lock()
-_refresh_events: dict[str, threading.Event] = {}  # resource URL -> "refresh in flight"
+_refresh_done = threading.Event()
+_refresh_done.set()
+
+def get_agent_access_token():
+    global _cached_token, _cached_token_expiry
 
-def get_agent_access_token(resource: str) -> str:
     with _cache_lock:
-        if resource in _cached_tokens and time.time() < _cached_expiries[resource]:
-            return _cached_tokens[resource]
+        if _cached_token and time.time() < _cached_token_expiry:
+            return _cached_token
 
         if not agent_identity_ready():
@@ -105,22 +102,13 @@ def get_agent_access_token(resource: str) -> str:
             )
 
-        # Only the first caller to see this resource's cache expired refreshes
-        # it; everyone else waits for that result below instead of firing its
-        # own request. The event is tracked only while that refresh is in
-        # flight, so the next expiry starts a fresh one.
-        event = _refresh_events.get(resource)
-        if event is None:
-            event = threading.Event()
-            _refresh_events[resource] = event
-            is_refresher = True
-        else:
-            is_refresher = False
+        # Only the first caller to see the cache expired refreshes it; everyone
+        # else waits for that result below instead of firing its own request.
+        is_refresher = _refresh_done.is_set()
+        if is_refresher:
+            _refresh_done.clear()
 
     if not is_refresher:
-        event.wait(timeout=15)
-        with _cache_lock:
-            if resource in _cached_tokens and time.time() < _cached_expiries[resource]:
-                return _cached_tokens[resource]
-        raise RuntimeError(f"Token refresh failed or timed out for {resource}")
+        _refresh_done.wait(timeout=15)
+        return _cached_token
 
     try:
@@ -130,5 +118,4 @@ def get_agent_access_token(resource: str) -> str:
                 "grant_type": "client_credentials",
                 "scope": AGENT_IDENTITY_SCOPES,
-                "resource": resource,
             },
             auth=(AGENT_IDENTITY_CLIENT_ID, AGENT_IDENTITY_CLIENT_SECRET),
@@ -139,17 +126,14 @@ def get_agent_access_token(resource: str) -> str:
 
         with _cache_lock:
-            _cached_tokens[resource] = token_data["access_token"]
+            _cached_token = token_data["access_token"]
             # Refresh at 75% of the token's lifetime, so a slow refresh never leaves a gap.
-            _cached_expiries[resource] = time.time() + (token_data["expires_in"] * 0.75)
+            _cached_token_expiry = time.time() + (token_data["expires_in"] * 0.75)
 
-        return _cached_tokens[resource]
+        return _cached_token
     finally:
-        with _cache_lock:
-            _refresh_events.pop(resource, None)
-        event.set()
+        _refresh_done.set()
 ```
 
-The same request with `curl`, useful for a quick manual check from inside the pod (replace
-`$MCP_SERVER_URL` with the target tool's own URL):
+The same request with `curl`, useful for a quick manual check from inside the pod:
 
 ```bash
@@ -157,6 +141,5 @@ curl -s -X POST "$AMP_AGENTID_TOKEN_ENDPOINT" \
   -u "$AMP_AGENTID_CLIENT_ID:$AMP_AGENTID_CLIENT_SECRET" \
   -d "grant_type=client_credentials" \
-  -d "scope=$AMP_AGENTID_SCOPES" \
-  -d "resource=$MCP_SERVER_URL"
+  -d "scope=$AMP_AGENTID_SCOPES"
 ```
 
@@ -164,10 +147,10 @@ curl -s -X POST "$AMP_AGENTID_TOKEN_ENDPOINT" \
 
 Attach the token as a bearer token on every call your agent makes to an MCP tool through the
-gateway. Request the token for that same tool's URL, since that's the resource it was minted
-for.
+gateway. This does not change which URL your agent calls, only which credential rides along
+with the call.
 
 ```python
 headers = {
-    "Authorization": f"Bearer {get_agent_access_token(mcp_gateway_url)}",
+    "Authorization": f"Bearer {get_agent_access_token()}",
 }
 response = requests.post(
```

</details>

### tutorials/create-your-first-agent

Main-line page `docs/tutorials/create-your-first-agent.mdx`; word F1 0.962.

<details><summary>Diff</summary>

```diff
--- main line: tutorials/create-your-first-agent.mdx
+++ Cloud: tutorials/create-your-first-agent.mdx
@@ -31,5 +31,5 @@ problem the previous one leaves behind, so they're meant to be read in order.
 ## What You'll Need
 
-- Agent Manager installed and reachable. [Quickstart](../get-started/quick-start.mdx) is the fastest route.
+- An Agent Manager Cloud account. Sign up at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/) if you don't have one yet.
 - An OpenAI API key.
 
@@ -57,29 +57,24 @@ where they appear.
 ## Step 1: Create the Agent
 
-Log in to the Agent Manager console using `admin` for both the username and password.
+Log in to the Agent Manager console at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/). There's no separate Agent Manager username or password to create: sign in with your existing Google or GitHub account, and Agent Manager Cloud federates that login for you.
 
-Where you land next depends on whether your organization already has a project.
-On a brand-new install with no projects yet, you'll land on the **Projects**
-view. That's the organization-wide screen listing every project across the org.
-If a project already exists (for example a `default` one created during setup),
-you're dropped straight into it instead.
+If you don't belong to an organization yet, you'll be prompted to create one first. Give it a **Name** and a **Handle** (a short, URL-safe identifier for your organization), then continue.
 
-Either way, get to the right project before creating anything:
+Every organization already has a **default** project, so you land directly
+inside it once you're logged in.
 
-- **Using an existing project**: open it from the project list, then skip
-  ahead to creating the agent below.
-- **Starting a new one**: from the **Projects** view (click the organization
-  icon next to the Agent Manager logo if you're not already there), click **Add
-  Project** and fill in:
+If you'd rather use a different project, go to the organization view (click
+the organization icon next to the Agent Manager logo), open **Projects**, and
+either select an existing one or click **Add Project** and fill in:
 
-  | Field | Value |
-  |---|---|
-  | **Name** | `it-support` |
-  | **Description** *(optional)* | `AcmeCorp IT helpdesk agents` |
-  | **Deployment Pipeline** | The pipeline that defines which environments (development, staging, production) this project's agents can be promoted through. See [Deployment Pipeline](../concepts/deployment-pipeline.mdx) if you don't have one yet. |
+| Field | Value |
+|---|---|
+| **Name** | `it-support` |
+| **Description** *(optional)* | `AcmeCorp IT helpdesk agents` |
+| **Deployment Pipeline** | The pipeline that defines which environments (development, staging, production) this project's agents can be promoted through. See [Deployment Pipeline](../concepts/deployment-pipeline.mdx) if you don't have one yet. |
 
-  You'll come back to this project in [Chapter 5](./promote-your-agent.mdx)
-  to promote the agent through that pipeline, so use `it-support` as the name
-  now.
+You'll come back to this project in [Chapter 5](./promote-your-agent.mdx)
+to promote the agent through that pipeline, so use `it-support` as the name
+now.
 
 If the project has no agents yet, you land directly on the **Add a New Agent**
```

</details>

### tutorials/deploy-the-a2a-notes-agent-sample

Main-line page `docs/tutorials/deploy-the-a2a-notes-agent-sample.mdx`; word F1 0.933.

<details><summary>Diff</summary>

```diff
--- main line: tutorials/deploy-the-a2a-notes-agent-sample.mdx
+++ Cloud: tutorials/deploy-the-a2a-notes-agent-sample.mdx
@@ -1,5 +1,2 @@
-import Tabs from '@theme/Tabs';
-import TabItem from '@theme/TabItem';
-
 # Deploy the A2A Notes Agent Sample
 
@@ -28,13 +25,9 @@ For how Agent Manager exposes A2A agents in general, see [Deploy an A2A Agent](.
 ## Prerequisites
 
-- WSO2 Agent Manager installed. See the [Quick Start Guide](../get-started/quick-start.mdx).
+- An Agent Manager Cloud account. Sign up at [console.agent-manager.cloud.wso2.com](https://console.agent-manager.cloud.wso2.com/) if you don't have one yet.
 - An OpenAI API key. Both skills call the model.
-- To use the CLI path: `amctl` installed and logged in. See [CLI Installation](../guides/cli-installation.mdx).
 
 ## Step 1: Create and Deploy the Agent
 
-<Tabs groupId="am-client">
-<TabItem value="console" label="Console" default>
-
 1. Open your project and click **Add Agent**.
 2. Choose **Platform-Hosted Agent**, then **Source Code** as the source type.
@@ -55,31 +48,4 @@ For how Agent Manager exposes A2A agents in general, see [Deploy an A2A Agent](.
 8. Click **Deploy**.
 
-</TabItem>
-<TabItem value="cli" label="amctl">
-
-```bash
-amctl agent create a2a-notes-agent \
-  --display-name "A2A Notes Agent" \
-  --subtype a2a-agent \
-  --port 9099 \
-  --repo-url https://github.com/wso2/agent-manager \
-  --repo-branch main \
-  --repo-path /samples/a2a-agent \
-  --build-type buildpack \
-  --language python \
-  --language-version 3.11 \
-  --run-command "python main.py" \
-  --env-secret OPENAI_API_KEY=<your-openai-key>
-
-amctl agent build create a2a-notes-agent
-amctl agent deploy a2a-notes-agent
-amctl agent status a2a-notes-agent
-```
-
-Replace `<your-openai-key>` with your OpenAI API key. `amctl agent deploy` deploys the newest build, and `amctl agent status` shows the deployment status and the agent's endpoint URL.
-
-</TabItem>
-</Tabs>
-
 The build takes a few minutes. When it finishes, the agent deploys to the first environment and the platform publishes it to the gateway.
 
@@ -194,4 +160,3 @@ Any A2A client works. Point it at the agent's card through the gateway, `<invoke
 |---|---|
 | [Deploy an A2A Agent](../guides/deploy-an-a2a-agent.mdx) | Deploying your own A2A agent, Agent Card CORS, and endpoint settings |
-| [Sample Agents](../reference/sample-agents.mdx) | The other samples in the repository |
 | [Create Your First Agent](create-your-first-agent.mdx) | The general agent creation flow |
```

</details>

### tutorials/govern-the-model

Main-line page `docs/tutorials/govern-the-model.mdx`; word F1 0.954.

<details><summary>Diff</summary>

```diff
--- main line: tutorials/govern-the-model.mdx
+++ Cloud: tutorials/govern-the-model.mdx
@@ -100,35 +100,15 @@ redeployments, and no agent ever held it in the first place.
 ## Step 2: Add the Guardrail
 
-Navigate to the provider's **Guardrails** tab and click **Add Guardrail**. Search
-for **Prompt Decorator** and select it.
-
-Under **promptDecoratorConfig**, add the instruction as a message rather than as
-text:
-
-1. Under **messages**, click **Add Item**.
-2. Set **Role** to `system`.
-3. In **Content**, enter an instruction like the following:
-
-    ```text
-    You handle IT support requests for AcmeCorp employees only: passwords, software
-    access, tickets, outages, and IT policy. If a request is not IT support, politely
-    decline and suggest the employee contact the relevant team. Never write code,
-    essays, or creative content.
-    ```
-
-Leave **Text** and **Json Path** empty. The decorator accepts exactly one of
-**text** or **messages**.
-
-:::note Why messages and not Text
-A **Text** decoration is inserted into a string field, by default the content of
-the last message (`$.messages[-1].content`). That works while every message is
-plain text. From the [next tutorial](./give-the-agent-real-tools.mdx) on, the
-agent calls tools, and after a tool call the last message is the tool's result.
-The sample sends that result's content as a list of content blocks rather than a
-string, so a **Text** decoration has no string to decorate. The gateway then
-rejects every request
-:::
+Navigate to the provider's Guardrails tab and select **Add Guardrail**. Search for **Prompt Decorator**, select it, and provide an instruction like the following:
+
+For the prompt decorator config
+```text
+You handle IT support requests for AcmeCorp employees only: passwords, software
+access, tickets, outages, and IT policy. If a request is not IT support, politely
+decline and suggest the employee contact the relevant team. Never write code,
+essays, or creative content.
+```
 
-Keep everything else at its default configuration and click **Add**.
+Keep everything else at its default configuration and click Add.
 
 Now scroll down and click Save to register the guardrail configuration.
```

</details>

### tutorials/promote-your-agent

Main-line page `docs/tutorials/promote-your-agent.mdx`; word F1 0.968.

<details><summary>Diff</summary>

```diff
--- main line: tutorials/promote-your-agent.mdx
+++ Cloud: tutorials/promote-your-agent.mdx
@@ -6,10 +6,9 @@ employees.
 
 :::info This chapter needs a platform-hosted agent
-Promotion, suspend, endpoint security, and isolation tiers are all things
-Agent Manager can only do for a workload it runs. If your agent is
-externally-hosted, follow along to understand the model. The actions
-themselves won't be available to you, and the deployment and endpoint
-security stay your responsibility. Only [Step 7](#step-7-watch-it) applies to
-both.
+Promotion, suspend, and endpoint security are all things Agent Manager can
+only do for a workload it runs. If your agent is externally-hosted, follow
+along to understand the model. The actions themselves won't be available to
+you, and the deployment and endpoint security stay your responsibility. Only
+[Step 7](#step-7-watch-it) applies to both.
 :::
 
@@ -34,7 +33,7 @@ development, then staging, then production.
 ```mermaid
 flowchart LR
-  B["Build<br/>one image"] -->|"env-non-production"| D["Development"]
-  D -->|"promote<br/>env-non-production"| S["Staging"]
-  S -->|"promote<br/>env-production"| P["Production"]
+  B["Build<br/>one image"] -->|"deploy-non-production"| D["Development"]
+  D -->|"promote<br/>deploy-non-production"| S["Staging"]
+  S -->|"promote<br/>deploy-production"| P["Production"]
 ```
 
@@ -176,11 +175,4 @@ Run the seeded traffic against staging one more time. Confirm the monitors
 from Chapter 4 are green. Then promote staging to production.
 
-When you promote into an environment, the agent runs under that
-environment's configured **Isolation Tier**, the sandboxing strength you
-chose (or left at default) when you created it in Step 1. If you want
-production locked down tighter than the default, set that on the environment
-before promoting into it. See
-[Environment Management](../guides/environment-management.mdx) for how.
-
 {/* SCREENSHOT: Promote dialog for staging to production, with the production configuration panel */}
 
@@ -191,9 +183,9 @@ file mounts it needs. Same pattern as Step 3, just for production this time.
 
 You may find you *can't* do this. That's the system working as intended.
-Promoting into production needs `amp:agent:env-production`,
-[held in addition to](../concepts/organization.mdx#production-is-a-separate-permission)
-the `amp:agent:env-non-production` you've been using all series, not instead
-of it. A **Developer** typically has the non-production scope but not the
-production one. A **Platform Engineer** has both.
+Promoting into production requires `amp:agent:deploy-production`,
+[a separate permission](../concepts/organization.mdx#production-is-a-separate-permission)
+from the `amp:agent:deploy-non-production` you've been using all series. A
+**Developer** typically has the non-production scope but not the production
+one. A **Platform Engineer** has both.
 
 The split is what makes the pipeline a control rather than a convention: the
@@ -246,4 +238,2 @@ than wiring each one by hand.
 
 - [Agent Kind & Agent Catalog](../concepts/agent-kind-and-catalog.mdx): publish this agent as a reusable template so other teams can deploy their own.
-- [Authorization](../reference/authorization.mdx): the full scope catalog behind the permission split you just hit.
-- [CLI](../reference/cli/overview.mdx): do all of this from `amctl` instead of the console.
```

</details>
