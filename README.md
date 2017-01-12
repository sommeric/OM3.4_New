# Ops Manager 3.4 User Interface Changes

Ops Manager 3.4, released at the beginning of December, contains both new feature and changes from the previous major release, 2.0. This blog post will focus on the new Ops Manager 3.4 UI. It will cover new features and highlight changes from the previous UI.
 

## Deployment page

Ops Manager 3.4 has a redesigned deployment page. Items that previously appeared in the inner left-hand navigation bar now appear as tabs. Joining the existing tab for Processes are tabs for Servers and Agents. Security settings also now appear under a separate Security tab. These include USERS, ROLES and AUTHORIZATION & TSL/SSL SETTINGS. The TOPOLOGY and LIST views are now accessed via buttons. Additional functions are accessible under More: Host Mappings, Version Manager, and Logs.

## Alerts tab

Ops Manager 2.0 featured dedicated icons on the top of page showing the health of the agents.

In Ops Manager 3.4, agent health is reported via alerts. These alerts function identically to all other alerts and appear in the Alerts tab. Agent alerts are active by default.

## Metrics

In Ops Manager 2.0, metric chart zoom and granularity are set via buttons. "Last Ping" information is accessed via the ellipsis button.

In Ops Manager 3.4, zoom and granularity were changed to drop-down menus, and an additional 10-second granularity setting was added for improved resolution. The granularity drop-down also has a new 'auto' setting which chooses the optimum granularity based on the display period.  "Last Ping" information is now listed under More. For HW metrics, use of munin-node is no longer required. HW metrics are automatically gathered for automated deployments.

## Documentation and Support

For Ops Manager 2.0, documentation and support were accessed via icons in the top-right corner of the page.

In Ops Manager 3.4, those are accessed via buttons at the bottom of the left-hand navigation bar.

## Admin Page

For Ops Manager 3.4, existing functionality on the Admin page remains identical to version 2.0. This page is also the location for accessing two new features: S3 blockstore configuration for backups (under the existing Backup button) and server pool administration (under the new Server Pool button). For more details on these fatures, see the Ops Manager documentation.
