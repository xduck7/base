.PHONY: new help

new:
ifndef NAME
	$(error Укажите имя проекта: make new NAME=ProjName)
endif
	cargo new $(NAME) --vcs none
	@echo "Создан проект '$(NAME)' без контроля версий"

help:
	@echo "Использование:"
	@echo "  make new NAME=ProjectName  - Создать новый проект без Git"
	@echo "  make help                 - Показать эту справку"