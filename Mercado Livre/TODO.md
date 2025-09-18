# TODO: Modificar Main-Banner para Ser Inteiramente uma Imagem com Gradiente Branco

## Passos para Implementação

1. **Editar HTML**: Remover o conteúdo interno da seção main-banner (banner-content, banner-info, banner-images) para deixar apenas a seção vazia.
2. **Atualizar CSS para .main-banner**: 
   - Definir background-image para a URL da imagem principal.
   - Adicionar background-size: cover e background-position: center.
   - Definir height: 400px e position: relative.
3. **Adicionar Gradiente Branco**: Criar um pseudo-elemento ::after com linear-gradient de branco transparente na parte inferior.
4. **Remover CSS Não Utilizado**: Excluir regras CSS para banner-content, banner-info, banner-images, pois o conteúdo foi removido.
5. **Testar**: Abrir index.html no navegador para verificar se o banner aparece como imagem inteira com gradiente.

## Status
- [x] Passo 1: Editar HTML
- [x] Passo 2: Atualizar CSS para .main-banner
- [x] Passo 3: Adicionar Gradiente Branco
- [x] Passo 4: Remover CSS Não Utilizado
- [x] Passo 5: Testar
