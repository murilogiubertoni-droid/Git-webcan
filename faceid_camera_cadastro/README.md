# FaceID Local — cadastro de rosto pela câmera

1. Extraia o ZIP e abra a pasta no VS Code.
2. Abra `index.html` com a extensão **Live Server** (recomendado), ou execute `python -m http.server 8000` e acesse `http://localhost:8000`.
3. Mantenha a internet ligada na primeira abertura para baixar biblioteca e modelos.
4. Clique em **Iniciar câmera** e permita o acesso à webcam.
5. Digite o nome da pessoa e clique em **Capturar rosto e cadastrar**. Deve haver apenas um rosto visível.
6. A câmera continuará analisando e mostrará o nome quando encontrar uma correspondência.

Os cadastros ficam na memória durante a sessão atual e são apagados ao recarregar a página. O processamento ocorre no navegador; modelos e biblioteca vêm de CDN. Use apenas com autorização. Protótipo educacional, pode errar e não deve ser usado como sistema de segurança.
