---
layout: post
title: B(TC)itcoin es lento
---

Bitcoin es lento porque el tamaño de bloque se dejó en 1MB - 2MB con Witness Data en red SEGWIT - tras tirar a todo el "equipo" desarrollador del GitHub y ser ocupado por desarrolladores de lo que hoy se conoce como Blockstream. 
Este tamaño se ha mantenido y mantiene aludiendo a dos cuestiones: La minería en China y la descentralización de los nodos ó validadores de transacciones que usted señala en el artículo. 

La minería en China ocupa buena parte de la tarta que se reparten los mineros - a su vez éstos son los que confirman las transacciones y minan los bloques - desde el 2011 y estas granjas chinas están detrás de una cosa que en Occidente denominan "El Gran Cortafuegos" que impide una conexión estable y ralentizan la propagación del bloque, su minado y la confirmación de la trasacción por encima de los 3 minutos[1][2] haciendo que una gran parte del minado venido de China y por tanto del poder de 'Hash' disminuyese drásticamente afectando a la seguridad de Bitcoin; A menor Hash mayor posibilidad de ser atacada la red de Bitcoin mediante un ataque del 51% que podría provocar un doble gasto - aunque esto da lugar a muchos debates ya que el ataque del 51% sobre una red ya "madura" como Bitcoin requiere un gasto considerable en equipos de minado para controlar el 51% del poder de minado y recibiendo la recompensa de bloque y las comisiones por transferencia confirmada sobre cada bloque haría menos probable que dicho minero o agrupación minera deseara realizar un doble gasto al recibir una compensación económica suficiente por lo que únicamente un agente malicioso con las intenciones de destruir la red y asumiendo las pérdidas totales sobre la inversión de equipos estaría dispuesto a llevar a cabo dicha operación. Posibilidades existen pero éstas se reducen al ser el minero compensado por su actividad. 

En las mismas referencias a las granjas de minería chinas pero en otro ámbito más económico; Bitcoin cuenta con 21 millones que se consiguen a través de minado y comisiones en las transferencias. Estos 21 millones se consiguen a lo largo del tiempo y a partir de ahí se convierte en un elemento deflacionario al no existir la posibilidad de impresión de más monedas. La cuestión del costreñimiento del bloque de Bitcoin y la influencia de la minería china pasa por el subsidio de Bitcoin o, actualmente denominado como, recompensa de bloque: Cuando un minero pone un bloque en la cadena éste recibe la recompensa de Bitcoin que hay "dentro" de ese bloque y que actualmente está cifrada en 12.5. Cada 210000 bloques la recompensa se reduce a la mitad por lo que en menos de un año (312 días a partir de hoy[3]) ésta se reducirá a 6.25 por lo que los mineros verán caer su subsidio a la mitad a no ser que el precio por moneda de Bitcoin aumente considerablemente o bien las granjas de minería comiencen a cerrar o reducir equipos mineros disminuyendo así la potencia de Hash de la red. Si Bitcoin reduce a la mitad cada 210000 bloques el subsidio por bloque a mineros llegará un momento en que éstos solo podrán vivir y mantener sus equipos por las comisiones de transacción y en una red de Bitcoin con 7 transacciones por segundo y una comisión que tiende a subir cuanto mayor es el número de movimientos en la misma hace inviable que los mineros continúen en dicha red de 1MB y sobretodo que la gente quiera utilizar este método de pago que es caro y lento - más incluso que el oro papel - Porque recordemos que Bitcoin nace como Peer 2 peer cash, no gold-. 
Por tanto, si en el tiempo el subsidio o recompensa va a ser 0 o incapaz de cubrir el gasto minero de equipos es necesario buscar una solución si los desarrolladores no quieren tocar el tamaño del bloque. Y ésta pasa por tres cuestiones ya planteadas en BIPs y sobre la comunidad: RPF (Replace By Fee), Lightning Network y Aumento del número de Bitcoin dado que la demanda de Bitcoin no sube porque ofreza un servicio de calidad sino por la seguridad y sobretodo por la manipulación de Tether (USDT) y las grandes casas de intercambio:  

 - El RBF consiste en la sustitución de una transacción sin confirmaciones por otra que la reemplazaría con una mayor comisión eliminando la anterior de la mempool - el limbo de las transacciones por confirmar en Bitcoin -. Este sistema si bien parece efectivo no elimina el problema a largo plazo de seguir manteniendo el bloque reducido sino que aleja el problema de la financiación de los mineros mas no lo elimina y sobretodo mata el funcionamiento de transacciones de Bitcoin al no eliminar el aumento en las comisiones que alejaría al usuario de su utilización. Además de permitir con mayor facilidad el doble gasto [4][5].

 - Lightning Network es un side-chain ó segunda capa, es decir, un desarrollo software no implementado en la propia red de Bitcoin y por tanto no es un elemento de la cadena de bloque por lo que esto ya debería ser repudiado ya que siendo un elemento externo y no auditable como Bitcoin da lugar a "espacios en blanco" y por tanto carecer de existencia y posibilidad de auditaje de cuentas [6] e incluso la perdida de dinero ó cancelación de la transacción [7][8]. También se enfrenta al problema de enrutado ya que en una red en constante cambio con las aperturas y cierres de canales de pago es inviable establecer una difusión total y rápida a los nodos de LN - distintos a los de Bitcoin - por lo que entra en juego otro elemento nuevo de dicha red que son las torres de vigilancia (watchtowers) encargadas de velar por el cumplimiento en los canales abiertos y sobre toda la red LN de los pagos. Evidentemente requiere un coste adicional contratar este servicio y todavía no está implementado [9] y teniendo en cuenta el ritmo al que se desarrolla Lightning Network se duda que llegue a estar disponible [10]. En definitiva, para utilizar apropiadamente - que no con éxito - LN necesitas un nodo valorado en 300$[11], una watchtower, tener un canal abierto 24/7 y con fondos suficientes para realizar transacciones [12][13][14].

 - El aumento de la oferta de Bitcoin fue planteado de manera fugaz por el desarrollador Peter Todd [15][16] y pasará a ser un debate abierto en unos años cuando la recompensa por bloque minado sea escasa y el precio de Bitcoin no pueda sustentarse solo con impresión descontrolada de Tether y la manipulación sobre el precio de la moneda [17][18] junto a la colusión de las casas de intercambio encabezada por BitFinex [19] y personalidades del mundo 'cripto' [20] - si es que llega a sobrevivir lo suficiente como para ver ese momento ya que ya van detrás de Bitfinex por lavado de dinero [21]. Cuando ese momento llegue estoy seguro que una BIP - Bitcoin Improvement Proposal - será lanzada por Blockstream o directamente se avisará de la medida destruyendo la esencia de Bitcoin y la VERDADERA DESCENTRALIZACIÓN: EL PROTOCOLO.

Esto nos lleva al segundo motivo de la lentitud de Bitcoin. La descentralización correcta y verdadera pasa por el código y el equipo de desarrolladores y mantenedores, no por ninguna otra. El protocolo debe ser grabado en piedra [22] y que la acción de los mineros distribuya y descentralice la red y éstos mantengan los nodos y las transacciones en una relación económica completamente capitalista. Invertir en máquinas y comunicación mejora el acceso, rapidez y propagación de las transacciones y bloques y convierte a los mineros en verdaderos competidores además de facilitar la transmisión de dinero y todo tipo de transacciones [22].
La descentralización de los nodos fue el otro gran motivo para impedir el aumento del bloque y por tanto la rapidez en la transacción. Se parte de una premisa falsa el basar la descentralización de Bitcoin - que no figura en ningún lado en el whitepaper - en los nodos raspberry. La dispersión de la transacción y todos los estadios de ésta y los bloques dependen del minero y su equipo así como de la búsqueda de la excelencia en las comunicaciones para evitar bloques huérfanos - que están estipulados en el consenso Nakamoto y forman parte de Bitcoin y no arrojan ningún problema en las transacciones solamente en la resolución de la recompensa del bloque que afecta a los mineros y deberán buscar una mayor eficiencia - y reorganizaciones. La auditoría sobre la red Bitcoin puede ser perfectamente realizada sin que haya un nodo de Bitcoin en cada casa, de hecho provocaría los mismos problemas de enrutado que ocurren/ocurrirán en la red LN.
La descentralización no debe pasar por los nodos sino por los desarrolladores y en menor medida por los mineros. Si un protocolo está continuamente siendo alterado por desarrolladores éstos tienen el poder de la red y éste debe estar en pugna constante por los mineros a través de la comisión en las transacciones.

Debido a estos dos factores se rechazó la BIP0101 propuesta por los desarrolladores que dejó a cargo Satoshi [23] y que originó la creación de Bitcoin Unlimited, posteriormente éste fue atacado debido a su reciente creación mediante ataques DDoS en una declaración de intenciones de la red Bitcoin de Blockstream [24][25] quedándose como un elemento residual.

Estos dos motivos son los causantes del ahogamiento que sufre la red de Bitcoin - incluídos muchos otros elementos que fueron eliminados y que correspondían al código inicial cambiando por completo la naturaleza y el destino de Bitcoin que no vienen al caso y no pasaré a enumerar -, cualquier otro motivo es propaganda por quienes quieren mantener ahogado Bitcoin para enriquecerse con los subisidios en la minería y los software de segunda capa como LN. Bitcoin tiene una estructura similar al oro y puede recoger ciertos atributos de éste pero su destino en la transmisión eficiente y rápida como efectivo - entre otras transacciones-.

Bitcoin fue diseñado para profesionalizar a los mineros y crear una nueva industria a su alrededor por lo que los centros de minado pasarán a ser datacenters [26] y éstos replicarán todos los logs de transacciones e incluso esta profesionalización acabará llevando a una especialización en otros tipo de transacciones naciendo nuevas industrias a su alrededor que respaldarán los nodos según la especialización - Datos, transmisiones de activos, dinero, derechos de propiedad, etc... - 

Bitcoin escala al infinito si dejan al protocolo lo suficientemente LIBRE como para que pueda hacerlo. 

Un saludo.

[1] https://np.reddit.com/r/btc/comments/3ygo96/blocksize_consensus_census/cye0bmt/

[2] https://www.youtube.com/watch?v=ivgxcEOyWNs&feature=youtu.be&t=2h36m20s

[3] https://www.bitcoinblockhalf.com/

[4] https://petertodd.org/2016/are-wallets-ready-for-rbf

[5] https://www.ccn.com/bitcoin-atm-double-spenders-police-need-help-identifying-four-criminals/

[6] https://bitcointalk.org/index.php?topic=4905430.0

[7]https://www.trustnodes.com/2018/03/26/lightning-network-user-loses-funds || https://www.trustnodes.com/2019/03/13/lightning-network-has-many-routing-problems-says-lead-dev-at-lightning-labs

[8] https://diar.co/volume-2-issue-25/

[9] https://blockonomi.com/watchtowers-bitcoin-lightning-network/

[10] https://twitter.com/starkness/status/676599570898419712

[11] https://store.casa/lightning-node/

[12] https://bitcoin.stackexchange.com/questions/81906/to-create-a-channel-on-the-lightning-network-do-you-have-to-execute-an-actual-t

[13] https://blog.muun.com/the-inbound-capacity-problem-in-the-lightning-network/

[14] https://medium.com/@octskyward/the-capacity-cliff-586d1bf7715e

[15] https://dashnews.org/peter-todd-argues-for-bitcoin-inflation-to-support-security/
[16] https://twitter.com/peterktodd/status/1092260891788103680
[17] https://medium.com/datadriveninvestor/tether-usd-is-used-to-manipulate-bitcoin-prices-94714e65ee31
[18] https://twitter.com/CryptoJetHammer/status/1149131155469455364
[19] https://www.bitrates.com/news/p/crypto-collusion-the-web-of-secrets-at-the-core-of-the-crypto-market
[20] https://archive.is/lk1lH
[21] https://iapps.courts.state.ny.us/nyscef/ViewDocument?docIndex=8W00ssb7x5ZOaj8HKFdbfQ==
[22] https://bitcointalk.org/index.php?topic=195.msg1611#msg1611
[23] https://github.com/bitcoin/bips/blob/master/bip-0101.mediawiki
[24] https://www.reddit.com/r/bitcoinxt/comments/3yewit/psa_if_youre_running_an_xt_node_in_stealth_mode/
[25] https://www.reddit.com/r/btc/comments/3yebzi/coinbase_down/
[26]https://bitcointalk.org/index.php?topic=532.msg6306#msg6306

