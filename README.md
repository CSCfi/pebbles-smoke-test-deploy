# Playbook to deploy pebbles-smoke-test

AKA an adventure in deploying stacks using Heat.

Might be incorporated into pebbles-deploy in the near future. Might not,
depends on philosophical things mostly.

For playbook structure refer to https://github.com/cscfi/pouta-ansible-cluster


To run set up environment, private vars and run

  ansible-playbook playbooks/site.yml -i \
  environments/notebooks-smoke-test/hosts -e \
  "cluster_name=notebooks-smoke-test group=notebooks-smoke-test"

getting rid of duplicate extra vars is in the queue.
