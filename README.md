# Ægis
A Iniciativa Aegis busca fortalecer a segurança cibernética no Brasil, criando um caminho estruturado para profissionais 
que desejam se especializar em pentest e segurança ofensiva. Baseada nos mais altos padrões, prepara seus membros para atuar 
em Red Team, Threat Hunting, testes de invasão e resposta a incidentes.

# Contribuindo
O conteúdo do site é gerado através da ferramenta DocFx (v2.78.3). Caso deseje propor novos conteúdos ou corrigir o que 
existe, valide suas alterações publicando localmente a página, antes de enviar ao repositório. Para isso, siga os 
passos abaixo.

Instale a última versão da ferramenta através do comando (se já existir, ele aplica a atualização automaticamente):
```
dotnet tool install docfx --global
```
Suba a versão em `localhost` usando:
```
docfx tool/docfx_project/docfx.json --serve
```

_Obs: lembre-se que se estiver lidando com menus, estes ficam nos arquivos `toc.yml`._

Caso deseje uma página global (sem sub-páginas), adicione o cabeçalho em sua `pagina.md`:

```
---
_layout: landing
---
```