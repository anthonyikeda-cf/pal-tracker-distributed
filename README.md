
```bash
./gradlew cloudNativeDeveloperDistributedSystemDeployment \
    -PregistrationServerUrl=https://registration-pal-ikeda.cfapps.io \
    -PbacklogServerUrl=https://backlog-pal-ikeda.cfapps.io \
    -PallocationsServerUrl=https://allocations-pal-ikeda.cfapps.io \
    -PtimesheetsServerUrl=https://timesheets-pal-ikeda.cfapps.io


./gradlew cloudNativeDeveloperDistributedSystemWithServiceDiscovery \
    -PregistrationServerUrl=https://registration-pal-ikeda.cfapps.io \
    -PbacklogServerUrl=https://backlog-pal-ikeda.cfapps.io \
    -PallocationsServerUrl=https://allocations-pal-ikeda.cfapps.io \
    -PtimesheetsServerUrl=https://timesheets-pal-ikeda.cfapps.io


./gradlew cloudNativeDeveloperDistributedSystemWithCircuitBreaker \
    -PregistrationServerUrl=https://registration-pal-ikeda.cfapps.io \
    -PbacklogServerUrl=https://backlog-pal-ikeda.cfapps.io \
    -PallocationsServerUrl=https://allocations-pal-ikeda.cfapps.io \
    -PtimesheetsServerUrl=https://timesheets-pal-ikeda.cfapps.io
```
