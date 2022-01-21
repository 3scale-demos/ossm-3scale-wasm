# Cluster Authentication using GitHub

1. Create a new OAuth app in GitHub and get your client ID and secret.
2. ClusterSettings->Global->OAuth->Add Provider
3. Create User group with all members
4. Add cluster role binding to the group

For reference configuration see resources included in this directory (`support/github-cluster-auth`).