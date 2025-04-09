install-infra:
	helm upgrade --install harbor-infra charts/infra --wait

install-app:
	helm upgrade --install harbor charts/app --dependency-update --wait

install: install-infra install-app

uninstall: uninstall-infra uninstall-app
uninstall-infra:
	helm uninstall harbor-infra

uninstall-app:
	helm uninstall harbor
