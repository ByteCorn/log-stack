# log-stack

SIEM c централизованным журналированием

# Устанавливаем владельца (UID 1000 - это пользователь wazuh/opensearch)
chown -R 1000:1000 ./wazuh_indexer_data ./wazuh_etc ./wazuh_logs

# На всякий случай даем права на чтение/запись
chmod -R 750 ./wazuh_indexer_data ./wazuh_etc ./wazuh_logs
