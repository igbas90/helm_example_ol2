при запуске добавить флаг --wait

```
cd otus_lab2
helm install . --wait --generate-name
```

миграции применяются по хуку post-install автоматом (migrate-job)

настройки на хост arch.homework
