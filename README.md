`npx expo install expo-image-picker`

### Configuração de permissões necessária no arquivo app.json:

Adicione (após a chave `web`) o recurso a seguir:

```json
"plugins": [
      [
        "expo-image-picker",
        {
          "photosPermission": "The app accesses your photos to let you share them with your friends."
        }
      ]
    ]
```
