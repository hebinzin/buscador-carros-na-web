# Busca de Carros

[CarrosnaWeb](https://www.carrosnaweb.com.br/)

## Parâmetros de busca:

_Acrescentar à URL `https://www.carrosnaweb.com.br/catalogo.asp?`_

- `vendaOficial` (booleano): `true` para filtrar por carros disponíveis no Brasil.
- `fabricante` (texto): Renault, Ford, etc.
- `varnome` (texto): Clio, Ka, etc.
- `codigoMotor` (texto): D4D, Sigma, etc.
- `plataforma` (texto): B-Car, etc.
- `cambio` (inteiro): 1 (manual), 2 (automático).
- `portas` (inteiro): 2, 4, etc.
- `valini` (inteiro): valor mínimo em reais. Ex.: 20000, 40000, etc.
- `valfim` (inteiro): valor máximo em reais. Ex.: 30000, 50000, etc.
- `anoini` (inteiro): ano mínimo do modelo. Ex.: 2007, 2014, etc.
- `anofim` (inteiro): ano máximo do modelo. Ex.: 2016, 2020, etc.
- `geracao` (inteiro): 3, 4, etc.
- `config` (inteiro): 1 (hatchback), 2 (sedã), 3 (perua), 7 (SUV), 9 (picape), 11 (conversível), etc.
- `porte` (inteiro): 1 (compacto), 2 (médio), 3 (grande), 4 (subcompacto), 5 (médio-compacto), etc.
- `passageiros` (inteiro): mínimo de passageiros. Ex.: 2, 4, 5, etc.
- `combustível` (caractere): F (flex), A (álcool), G (gasolina), etc.
- `pesotorqmin` (inteiro): peso/torque mínimo em Kg. Ex.: 64.
- `pesotorqmax` (inteiro): peso/torque máximo em Kg. Ex.: 78.
- `pesopotmin` (inteiro): peso/potência mínimo em Kg. Ex.: 9
- `pesopotmax` (inteiro): peso/potência máximo em Kg. Ex.: 11
- `portamalas` (inteiro): tamanho mínimo do porta-malas em litros. Ex.: 250, 300, etc.
- `cilini` (inteiro): mínimo de cilindradas em mililitros. Ex.: 999, etc.
- `cilfim` (inteiro): máximo de cilindradas em mililitros. Ex.: 1500, etc.
- `proced` (inteiro): procedência. 1 (nacional), 2 (importado).
- `consumoUrbano` (inteiro): consumo urbano mínimo em Km por litro. Ex.: 6
- `consumoEstrada` (inteiro): consumo mínimo na estrada em Km por litro. Ex. 10
- `alturasolo` (inteiro): altura mínima do solo em milímetros. Ex.: 120, 150.
- `embreagem` (texto): tipo da embreagem. Exemplos:
  + `Embreagem+monodisco+a+seco`
  + `Conversor+de+torque`.
- `direcao` (texto): tipo da direção. Exemplos:
  + `N%E3o+assistida`
  + `Hidr%E1ulica`
  + `El%E9trica`
  + `Eletro-hidr%E1ulica`
- `tanque` (inteiro): capacidade mínima do tanque em litros. Ex.: 45.
- `autonomiaCidade` (inteiro): autonomia urbana mínima em Km. Ex.: 350, 480.
- `autonomiaEstrada` (inteiro): autonomia mínima na estrada em Km. Ex.: 470, 550.
- `marchas` (inteiro). Número e marchas. Ex.: 4, 5, 6.
- `alimentacao` (texto). Tipo do sistema de injeção. Exemplos:
  + `Carburador`
  + `Inje%E7%E3o+monoponto`
  + `Inje%E7%E3o+multiponto`
  + `Inje%E7%E3o+direta`
- `ordem` (inteiro). Critério de ordem dos resultados. Exemplos:
  + 3 - melhor relação peso/potência.
  + 8 - melhor consumo rodoviário.
  + 9 - melhor consumo urbano.
  + 12 - carros mais baratos.
  + 13 - carros mais novos.
  + 20 - carros mais caros.
  + 27 - melhor relação peso/torque.
  + 91 - carros mais antigos.
- `eq##`: define características específicos quando atribuído o valor `on`. Ex.:
  + `eq01=on`: ar condicionado.
  + `eq09=on`: alarme antifurto.
  + `eq11=on`: airbags frontais.
  + `eq12=on`: airbags laterais.
  + `eq14=on`: câmera traseira para manobras.
  + `eq16=on`: computador de bordo.
  + `eq19=on`: controle de estabilidade.
  + `eq20=on`: controle de tração.
  + `eq21=on`: controle elétrico dos vidros dianteiros.
  + `eq22=on`: controle elétrico dos vidros traseiros.
  + `eq24=on`: encosto de cabeça para todos os ocupantes.
  + `eq25=on`: faróis com lâmpadas de LED ou similar.
  + `eq26=on`: faróis de neblina.
  + `eq29=on`: freios ABS.
  + `eq30=on`: interface bluetooth.
  + `eq31=on`: limpador e lavador do vidro traseiro.
  + `eq34=on`: rádio.
  + `eq40=on`: sensores de estacionamento traseiro.
  + `eq42=on`: travamento central das portas.
  + `eq44=on`: banco traseiro bipartido.
  + `eq60=on`: banco traseiro rebatível.
  + `eq65=on`: conexão USB
  + `eq69=on`: direção assistida.
  + `eq75=on`: câmbio automático.
  + `eq82=on`: sistema start stop.
  + `eq100=on`: espelhamento da tela do celular.
- `submit1` (texto). Valor fixo: `Buscar`
