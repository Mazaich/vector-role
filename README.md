# Vector Role

Устанавливает и настраивает Vector (лог-процессор) на CentOS/RHEL.

## Переменные

| Имя | Значение по умолчанию | Описание |
|-----|----------------------|----------|
| `vector_version` | `0.21.0` | Версия Vector |
| `vector_config_dir` | `/etc/vector` | Директория конфигурации |
| `vector_data_dir` | `/var/lib/vector` | Директория для данных |

## Зависимости

Нет.

## Пример плейбука

```yaml
- hosts: vector
  roles:
    - vector-role
