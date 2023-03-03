# amazon-instance-scan

US

This Nuclei template sends GET requests to the root directory, /admin, and /phpmyadmin, which are commonly used for web-based administration interfaces. The template uses filters to search for words and regular expressions in the response body, which may indicate the presence of AWS access keys or other sensitive information. The matchers are used to check for AWS-specific keywords, such as "EC2" and "Lambda", and to ensure that the HTTP response code is valid.  You can customize this template to fit your specific needs, such as adding additional paths to scan or modifying the filter and matcher rules to search for specific keywords or patterns.

BR

Este modelo envia solicitações GET para o diretório raiz, /admin e /phpmyadmin, que são comumente usados para interfaces de administração baseadas na web. O modelo utiliza filtros para procurar palavras e expressões regulares no corpo da resposta, que podem indicar a presença de chaves de acesso AWS ou outras informações sensíveis. Os verificadores são usados para verificar palavras-chave específicas da AWS, como "EC2" e "Lambda", e garantir que o código de resposta HTTP seja válido.

Você pode personalizar este modelo para atender às suas necessidades específicas, como adicionar caminhos adicionais para escanear ou modificar as regras de filtro e verificador para procurar palavras-chave ou padrões específicos.
