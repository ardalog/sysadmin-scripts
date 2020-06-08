Diretório de scripts para software laboratorial Scola.

- backup.ps1\
Script para Backup do Banco de dados Scola.\
 Efetua o DUMP do SQL\
 Formata o HD Externo utilizado no processo de backup\
 Copia o conteúdo pro HD externo\
 Verifica as chaves SHA1 do arquivo no servidor e do copiado pro HD externo para verificar se a cópia foi concluída com êxito\
 Ejeta o mesmo\
 Compacta o backup para permitir o upload em serviços de núvem (Google Drive, MEGA, OneDrive...)\
 Efetua a cópia do arquivo compactado para um compartilhamento windows da rede.\
 Notifica o início/término de cada etapa no Telegram para acompanhamento pelo sysadmin. \


