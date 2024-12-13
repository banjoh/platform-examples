install-infra:
	helm upgrade --install harbor-infra charts/infra

install-app:
	helm upgrade --install harbor charts/app --dependency-update

install: install-infra install-app
