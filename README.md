# VIPER-swift-template-for-generamba
Convenience template for generating code for VIPER Module

### How to use

 1. Install [generamba](https://github.com/rambler-digital-solutions/Generamba)
 2. [Add template](https://github.com/rambler-digital-solutions/Generamba/wiki/Available-Commands#template-installation)
 2. Add [transition helper](https://github.com/wowlocal/viper-transition-handler) to your project
 3. Open your project **root** directory on terminal and run `generamba gen [MODULE_NAME] swift_viper` ... profit 😎
---
### File structure
```
├── Assembly
│   └── YOUR_MODULE_NAMEModuleAssembler.swift # Inject your dependencies heare
├── Interactor
│   ├── YOUR_MODULE_NAMEInteractor.swift
│   ├── YOUR_MODULE_NAMEInteractorInput.swift
│   └── YOUR_MODULE_NAMEInteractorOutput.swift
├── Presenter
│   ├── YOUR_MODULE_NAMEModuleInput.swift
│   ├── YOUR_MODULE_NAMEModuleOutput.swift
│   └── YOUR_MODULE_NAMEPresenter.swift
├── Router
│   ├── YOUR_MODULE_NAMERouter.swift
│   └── YOUR_MODULE_NAMERouterInput.swift
├── View
│   ├── YOUR_MODULE_NAMEView.swift
│   ├── YOUR_MODULE_NAMEViewController.swift
│   ├── YOUR_MODULE_NAMEViewInput.swift
│   └── YOUR_MODULE_NAMEViewOutput.swift
└── YOUR_MODULE_NAMEModule.swift # Module spec for transition helper
```
