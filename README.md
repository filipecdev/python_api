# python_api

## Directórios
|Pasta|Função|
|-|-|
|`app/api/`|	Define os endpoints (camada de apresentação)|
|`app/core/`|	Configurações globais, constantes, middlewares|
|`app/models/`|	ORM: tabelas do banco e mapeamentos|
|`app/schemas/`|	Schemas de entrada/saída (validação e serialização)|
|`app/services/`|	Regras de negócio (serviços principais)|
|`app/repositories/`|	CRUD e lógica de acesso ao banco (abstração da base de dados)|
|`app/db/`|	Configuração do banco e ORM (engine, base, etc.)|
|`app/utils/`|	Funções utilitárias ou helpers reutilizáveis|
|`tests/`|Testes organizados por contexto|
|`migrations/`|	Arquivos de migração do banco (usando Alembic, Flask-Migrate, etc.)|
