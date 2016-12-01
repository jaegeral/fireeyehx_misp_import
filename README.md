#fireeyehx_misp_import

Import module for Fireeye HX Alerts

The idea is that you have an HX controller with N clients running HX. This import module should pull alerts from your HX controller and create events for each alert (correlated by client)

#Installation

Check out https://github.com/MISP/misp-modules

#Testing

update the values to your needs

modify the API Key:
```
cd _hx
cp config.example.cfg config.cfg
vi config.cfg
#change the values
```

#Running

#HX Documentation

https://docs.fireeye.com/docs/index.html#HX

#Issues

* https://github.com/deralexxx/fireeyehx_misp_import/issues

#Roadmap

*too much

#Other

## MISP
Want to learn about MISP: http://www.misp-project.org/