# Denver Launcher — releases

Repositório público do launcher do servidor **Denver** (RedM).

- **Baixar o launcher:** aba [Releases](../../releases/latest) → `Denver-Setup-x.y.z.exe`.
- `news.json`: notícias exibidas no launcher. Editar e dar push aqui atualiza todos os
  launchers (o GitHub pode levar ~5 min para servir a versão nova).
- `news/`: imagens das notícias (use `https://raw.githubusercontent.com/RedmDenverRP/denver-launcher-releases/main/news/<arquivo>`).

Formato de cada item de `news.json`:

| Campo | Obrigatório | Observação |
|---|---|---|
| `id` | sim | único |
| `title` | sim | até 80 caracteres |
| `tag` | não | até 24 |
| `date` | não | `AAAA-MM-DD` |
| `description` | não | até 400 |
| `image` | não | só https; ~430×280 |
| `url` | não | só https; o card abre o link ao clicar |

Até 20 itens. O código do launcher fica em um repositório privado da organização.
