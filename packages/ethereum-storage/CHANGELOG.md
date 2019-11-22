# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.4.5](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.4.4...@requestnetwork/ethereum-storage@0.4.5) (2019-11-20)

**Note:** Version bump only for package @requestnetwork/ethereum-storage





## [0.4.4](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.4.3...@requestnetwork/ethereum-storage@0.4.4) (2019-10-21)


### Bug Fixes

* **ethereum-storage:** checkEthereumNodeConnection never finishing when Ethereum node not reachable ([6941bd9](https://github.com/RequestNetwork/requestNetwork/commit/6941bd9))
* skip fetching data if no hash was found ([#545](https://github.com/RequestNetwork/requestNetwork/issues/545)) ([9583b8d](https://github.com/RequestNetwork/requestNetwork/commit/9583b8d))






## [0.4.3](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.4.2...@requestnetwork/ethereum-storage@0.4.3) (2019-09-16)

**Note:** Version bump only for package @requestnetwork/ethereum-storage





## [0.4.2](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.4.1...@requestnetwork/ethereum-storage@0.4.2) (2019-09-05)


### Bug Fixes

* retry twice to parse data on IPFS during initialisation of data-access ([#497](https://github.com/RequestNetwork/requestNetwork/issues/497)) ([c8d542d](https://github.com/RequestNetwork/requestNetwork/commit/c8d542d))






## [0.4.1](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.4.0...@requestnetwork/ethereum-storage@0.4.1) (2019-08-19)


### Performance Improvements

* lower concurrency to 5 and disable DHT on IPFS ([#500](https://github.com/RequestNetwork/requestNetwork/issues/500)) ([cec31e3](https://github.com/RequestNetwork/requestNetwork/commit/cec31e3))






# [0.3.0](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.1.1-alpha.4...@requestnetwork/ethereum-storage@0.3.0) (2019-07-24)


### Bug Fixes

* add retry for getPastEvents web3 API call ([#455](https://github.com/RequestNetwork/requestNetwork/issues/455)) ([0116636](https://github.com/RequestNetwork/requestNetwork/commit/0116636))
* block not found error in function addHashAndSizeToEthereum of storage ([#349](https://github.com/RequestNetwork/requestNetwork/issues/349)) ([1fea138](https://github.com/RequestNetwork/requestNetwork/commit/1fea138))
* Check the ipfs node connection getting an expected file instead of using repo/verify ([#440](https://github.com/RequestNetwork/requestNetwork/issues/440)) ([4d537f7](https://github.com/RequestNetwork/requestNetwork/commit/4d537f7))
* Data access synchronization not parallelized ([#333](https://github.com/RequestNetwork/requestNetwork/issues/333)) ([cd63a22](https://github.com/RequestNetwork/requestNetwork/commit/cd63a22))
* Error block XXX not found ([#306](https://github.com/RequestNetwork/requestNetwork/issues/306)) ([6c9c59b](https://github.com/RequestNetwork/requestNetwork/commit/6c9c59b))
* Ethereum-storage meta, no redundant getPastEvents call ([#312](https://github.com/RequestNetwork/requestNetwork/issues/312)) ([28b5bb1](https://github.com/RequestNetwork/requestNetwork/commit/28b5bb1))
* merge issue in ipfs pin config ([#413](https://github.com/RequestNetwork/requestNetwork/issues/413)) ([3a5654f](https://github.com/RequestNetwork/requestNetwork/commit/3a5654f))
* Misc. minor fixes on the request node ([#334](https://github.com/RequestNetwork/requestNetwork/issues/334)) ([8fcf53d](https://github.com/RequestNetwork/requestNetwork/commit/8fcf53d))
* query returned more than 10000 results error ([#437](https://github.com/RequestNetwork/requestNetwork/issues/437)) ([9621633](https://github.com/RequestNetwork/requestNetwork/commit/9621633))
* remove IPFS swarm connect from node initialization ([#442](https://github.com/RequestNetwork/requestNetwork/issues/442)) ([da11afa](https://github.com/RequestNetwork/requestNetwork/commit/da11afa))
* return ipfs-manager rejections ([#434](https://github.com/RequestNetwork/requestNetwork/issues/434)) ([0bc2b73](https://github.com/RequestNetwork/requestNetwork/commit/0bc2b73))
* skip flaky retry tests ([#427](https://github.com/RequestNetwork/requestNetwork/issues/427)) ([68dd837](https://github.com/RequestNetwork/requestNetwork/commit/68dd837))
* storage endless http request ([#284](https://github.com/RequestNetwork/requestNetwork/issues/284)) ([9adac9a](https://github.com/RequestNetwork/requestNetwork/commit/9adac9a))
* Storage Infura 1000 results error ([#320](https://github.com/RequestNetwork/requestNetwork/issues/320)) ([289a7f2](https://github.com/RequestNetwork/requestNetwork/commit/289a7f2))
* Use getSecondtLastBlockNumber instead of getLastBlockNumber for getBlockNumbersFromTimestamp ([#330](https://github.com/RequestNetwork/requestNetwork/issues/330)) ([58606b7](https://github.com/RequestNetwork/requestNetwork/commit/58606b7))
* use IPFS id endpoint to verify if the server is online ([#450](https://github.com/RequestNetwork/requestNetwork/issues/450)) ([ce56b5f](https://github.com/RequestNetwork/requestNetwork/commit/ce56b5f))
* use keyv to persist Ethereum metadata cache ([#431](https://github.com/RequestNetwork/requestNetwork/issues/431)) ([6a6788b](https://github.com/RequestNetwork/requestNetwork/commit/6a6788b))


### Features

* add concurrent readMany to storage layer ([#363](https://github.com/RequestNetwork/requestNetwork/issues/363)) ([db3f484](https://github.com/RequestNetwork/requestNetwork/commit/db3f484))
* add IPFS peer for faster IPFS retrieval, and check IPFS and Ethereum nodes connections ([#353](https://github.com/RequestNetwork/requestNetwork/issues/353)) ([47358c2](https://github.com/RequestNetwork/requestNetwork/commit/47358c2))
* add logging interfaces and default logger ([#397](https://github.com/RequestNetwork/requestNetwork/issues/397)) ([f83a716](https://github.com/RequestNetwork/requestNetwork/commit/f83a716))
* add script to configure private IPFS network ([#458](https://github.com/RequestNetwork/requestNetwork/issues/458)) ([4490d2b](https://github.com/RequestNetwork/requestNetwork/commit/4490d2b))
* add tags for successfully retrieved hashes ([#444](https://github.com/RequestNetwork/requestNetwork/issues/444)) ([cfc3eb0](https://github.com/RequestNetwork/requestNetwork/commit/cfc3eb0))
* add the ability to be able to configure the host + port via com… ([#355](https://github.com/RequestNetwork/requestNetwork/issues/355)) ([5b6a6c6](https://github.com/RequestNetwork/requestNetwork/commit/5b6a6c6))
* Add the two new IPFS nodes as known IPFS nodes ([#410](https://github.com/RequestNetwork/requestNetwork/issues/410)) ([b33f2e9](https://github.com/RequestNetwork/requestNetwork/commit/b33f2e9))
* additional node logs to show progress and logLevel option ([#338](https://github.com/RequestNetwork/requestNetwork/issues/338)) ([38559f4](https://github.com/RequestNetwork/requestNetwork/commit/38559f4))
* asynchronously pin IPFS files in batches ([#403](https://github.com/RequestNetwork/requestNetwork/issues/403)) ([926c22b](https://github.com/RequestNetwork/requestNetwork/commit/926c22b))
* check if the contracts are deployed and configured ([#360](https://github.com/RequestNetwork/requestNetwork/issues/360)) ([c18bf00](https://github.com/RequestNetwork/requestNetwork/commit/c18bf00))
* class to get Ethereum block information in storage ([#283](https://github.com/RequestNetwork/requestNetwork/issues/283)) ([1454981](https://github.com/RequestNetwork/requestNetwork/commit/1454981))
* configurable ethereum node host and port for smart contract deployment ([#358](https://github.com/RequestNetwork/requestNetwork/issues/358)) ([d7ad242](https://github.com/RequestNetwork/requestNetwork/commit/d7ad242))
* Create usable Dockerfile ([#278](https://github.com/RequestNetwork/requestNetwork/issues/278)) ([6c83f28](https://github.com/RequestNetwork/requestNetwork/commit/6c83f28))
* determines gas price automatically on mainnet ([#429](https://github.com/RequestNetwork/requestNetwork/issues/429)) ([3d42c75](https://github.com/RequestNetwork/requestNetwork/commit/3d42c75))
* implements cached-throttle utility ([#348](https://github.com/RequestNetwork/requestNetwork/issues/348)) ([01c9885](https://github.com/RequestNetwork/requestNetwork/commit/01c9885))
* IPFS retry on error  ([#421](https://github.com/RequestNetwork/requestNetwork/issues/421)) ([18d6e6e](https://github.com/RequestNetwork/requestNetwork/commit/18d6e6e))
* Migrate the synchronization from storage to data-access ([#292](https://github.com/RequestNetwork/requestNetwork/issues/292)) ([3d04d0d](https://github.com/RequestNetwork/requestNetwork/commit/3d04d0d))
* pin ipfs data on the node ([#361](https://github.com/RequestNetwork/requestNetwork/issues/361)) ([5830350](https://github.com/RequestNetwork/requestNetwork/commit/5830350))
* Save dataId's Ethereum metadata when append is called ([#352](https://github.com/RequestNetwork/requestNetwork/issues/352)) ([118d197](https://github.com/RequestNetwork/requestNetwork/commit/118d197))
* Storage cache for Ethereum metadata ([#323](https://github.com/RequestNetwork/requestNetwork/issues/323)) ([cb29b8e](https://github.com/RequestNetwork/requestNetwork/commit/cb29b8e))
* Storage get data from timestamp boundaries ([#291](https://github.com/RequestNetwork/requestNetwork/issues/291)) ([e9554cd](https://github.com/RequestNetwork/requestNetwork/commit/e9554cd))
* upgradable smart contracts ([#337](https://github.com/RequestNetwork/requestNetwork/issues/337)) ([c8cf724](https://github.com/RequestNetwork/requestNetwork/commit/c8cf724))


### Performance Improvements

* add the node ipfs request network at initialization ([#398](https://github.com/RequestNetwork/requestNetwork/issues/398)) ([7e0c25a](https://github.com/RequestNetwork/requestNetwork/commit/7e0c25a))
* faster initialization by factoring stat and read IPFS calls in one call ([#401](https://github.com/RequestNetwork/requestNetwork/issues/401)) ([184c14e](https://github.com/RequestNetwork/requestNetwork/commit/184c14e))





## [0.2.1-alpha.0](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.1.1-alpha.4...@requestnetwork/ethereum-storage@0.2.1-alpha.0) (2019-07-22)


### Bug Fixes

* add retry for getPastEvents web3 API call ([#455](https://github.com/RequestNetwork/requestNetwork/issues/455)) ([0116636](https://github.com/RequestNetwork/requestNetwork/commit/0116636))
* block not found error in function addHashAndSizeToEthereum of storage ([#349](https://github.com/RequestNetwork/requestNetwork/issues/349)) ([1fea138](https://github.com/RequestNetwork/requestNetwork/commit/1fea138))
* Check the ipfs node connection getting an expected file instead of using repo/verify ([#440](https://github.com/RequestNetwork/requestNetwork/issues/440)) ([4d537f7](https://github.com/RequestNetwork/requestNetwork/commit/4d537f7))
* Data access synchronization not parallelized ([#333](https://github.com/RequestNetwork/requestNetwork/issues/333)) ([cd63a22](https://github.com/RequestNetwork/requestNetwork/commit/cd63a22))
* Error block XXX not found ([#306](https://github.com/RequestNetwork/requestNetwork/issues/306)) ([6c9c59b](https://github.com/RequestNetwork/requestNetwork/commit/6c9c59b))
* Ethereum-storage meta, no redundant getPastEvents call ([#312](https://github.com/RequestNetwork/requestNetwork/issues/312)) ([28b5bb1](https://github.com/RequestNetwork/requestNetwork/commit/28b5bb1))
* merge issue in ipfs pin config ([#413](https://github.com/RequestNetwork/requestNetwork/issues/413)) ([3a5654f](https://github.com/RequestNetwork/requestNetwork/commit/3a5654f))
* Misc. minor fixes on the request node ([#334](https://github.com/RequestNetwork/requestNetwork/issues/334)) ([8fcf53d](https://github.com/RequestNetwork/requestNetwork/commit/8fcf53d))
* query returned more than 10000 results error ([#437](https://github.com/RequestNetwork/requestNetwork/issues/437)) ([9621633](https://github.com/RequestNetwork/requestNetwork/commit/9621633))
* remove IPFS swarm connect from node initialization ([#442](https://github.com/RequestNetwork/requestNetwork/issues/442)) ([da11afa](https://github.com/RequestNetwork/requestNetwork/commit/da11afa))
* return ipfs-manager rejections ([#434](https://github.com/RequestNetwork/requestNetwork/issues/434)) ([0bc2b73](https://github.com/RequestNetwork/requestNetwork/commit/0bc2b73))
* skip flaky retry tests ([#427](https://github.com/RequestNetwork/requestNetwork/issues/427)) ([68dd837](https://github.com/RequestNetwork/requestNetwork/commit/68dd837))
* storage endless http request ([#284](https://github.com/RequestNetwork/requestNetwork/issues/284)) ([9adac9a](https://github.com/RequestNetwork/requestNetwork/commit/9adac9a))
* Storage Infura 1000 results error ([#320](https://github.com/RequestNetwork/requestNetwork/issues/320)) ([289a7f2](https://github.com/RequestNetwork/requestNetwork/commit/289a7f2))
* Use getSecondtLastBlockNumber instead of getLastBlockNumber for getBlockNumbersFromTimestamp ([#330](https://github.com/RequestNetwork/requestNetwork/issues/330)) ([58606b7](https://github.com/RequestNetwork/requestNetwork/commit/58606b7))
* use IPFS id endpoint to verify if the server is online ([#450](https://github.com/RequestNetwork/requestNetwork/issues/450)) ([ce56b5f](https://github.com/RequestNetwork/requestNetwork/commit/ce56b5f))
* use keyv to persist Ethereum metadata cache ([#431](https://github.com/RequestNetwork/requestNetwork/issues/431)) ([6a6788b](https://github.com/RequestNetwork/requestNetwork/commit/6a6788b))


### Features

* add concurrent readMany to storage layer ([#363](https://github.com/RequestNetwork/requestNetwork/issues/363)) ([db3f484](https://github.com/RequestNetwork/requestNetwork/commit/db3f484))
* add IPFS peer for faster IPFS retrieval, and check IPFS and Ethereum nodes connections ([#353](https://github.com/RequestNetwork/requestNetwork/issues/353)) ([47358c2](https://github.com/RequestNetwork/requestNetwork/commit/47358c2))
* add logging interfaces and default logger ([#397](https://github.com/RequestNetwork/requestNetwork/issues/397)) ([f83a716](https://github.com/RequestNetwork/requestNetwork/commit/f83a716))
* add tags for successfully retrieved hashes ([#444](https://github.com/RequestNetwork/requestNetwork/issues/444)) ([cfc3eb0](https://github.com/RequestNetwork/requestNetwork/commit/cfc3eb0))
* add the ability to be able to configure the host + port via com… ([#355](https://github.com/RequestNetwork/requestNetwork/issues/355)) ([5b6a6c6](https://github.com/RequestNetwork/requestNetwork/commit/5b6a6c6))
* Add the two new IPFS nodes as known IPFS nodes ([#410](https://github.com/RequestNetwork/requestNetwork/issues/410)) ([b33f2e9](https://github.com/RequestNetwork/requestNetwork/commit/b33f2e9))
* additional node logs to show progress and logLevel option ([#338](https://github.com/RequestNetwork/requestNetwork/issues/338)) ([38559f4](https://github.com/RequestNetwork/requestNetwork/commit/38559f4))
* asynchronously pin IPFS files in batches ([#403](https://github.com/RequestNetwork/requestNetwork/issues/403)) ([926c22b](https://github.com/RequestNetwork/requestNetwork/commit/926c22b))
* check if the contracts are deployed and configured ([#360](https://github.com/RequestNetwork/requestNetwork/issues/360)) ([c18bf00](https://github.com/RequestNetwork/requestNetwork/commit/c18bf00))
* class to get Ethereum block information in storage ([#283](https://github.com/RequestNetwork/requestNetwork/issues/283)) ([1454981](https://github.com/RequestNetwork/requestNetwork/commit/1454981))
* configurable ethereum node host and port for smart contract deployment ([#358](https://github.com/RequestNetwork/requestNetwork/issues/358)) ([d7ad242](https://github.com/RequestNetwork/requestNetwork/commit/d7ad242))
* Create usable Dockerfile ([#278](https://github.com/RequestNetwork/requestNetwork/issues/278)) ([6c83f28](https://github.com/RequestNetwork/requestNetwork/commit/6c83f28))
* determines gas price automatically on mainnet ([#429](https://github.com/RequestNetwork/requestNetwork/issues/429)) ([3d42c75](https://github.com/RequestNetwork/requestNetwork/commit/3d42c75))
* implements cached-throttle utility ([#348](https://github.com/RequestNetwork/requestNetwork/issues/348)) ([01c9885](https://github.com/RequestNetwork/requestNetwork/commit/01c9885))
* IPFS retry on error  ([#421](https://github.com/RequestNetwork/requestNetwork/issues/421)) ([18d6e6e](https://github.com/RequestNetwork/requestNetwork/commit/18d6e6e))
* Migrate the synchronization from storage to data-access ([#292](https://github.com/RequestNetwork/requestNetwork/issues/292)) ([3d04d0d](https://github.com/RequestNetwork/requestNetwork/commit/3d04d0d))
* pin ipfs data on the node ([#361](https://github.com/RequestNetwork/requestNetwork/issues/361)) ([5830350](https://github.com/RequestNetwork/requestNetwork/commit/5830350))
* Save dataId's Ethereum metadata when append is called ([#352](https://github.com/RequestNetwork/requestNetwork/issues/352)) ([118d197](https://github.com/RequestNetwork/requestNetwork/commit/118d197))
* Storage cache for Ethereum metadata ([#323](https://github.com/RequestNetwork/requestNetwork/issues/323)) ([cb29b8e](https://github.com/RequestNetwork/requestNetwork/commit/cb29b8e))
* Storage get data from timestamp boundaries ([#291](https://github.com/RequestNetwork/requestNetwork/issues/291)) ([e9554cd](https://github.com/RequestNetwork/requestNetwork/commit/e9554cd))
* upgradable smart contracts ([#337](https://github.com/RequestNetwork/requestNetwork/issues/337)) ([c8cf724](https://github.com/RequestNetwork/requestNetwork/commit/c8cf724))


### Performance Improvements

* add the node ipfs request network at initialization ([#398](https://github.com/RequestNetwork/requestNetwork/issues/398)) ([7e0c25a](https://github.com/RequestNetwork/requestNetwork/commit/7e0c25a))
* faster initialization by factoring stat and read IPFS calls in one call ([#401](https://github.com/RequestNetwork/requestNetwork/issues/401)) ([184c14e](https://github.com/RequestNetwork/requestNetwork/commit/184c14e))





# [0.2.0](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.1.1-alpha.4...@requestnetwork/ethereum-storage@0.2.0) (2019-06-06)


### Bug Fixes

* block not found error in function addHashAndSizeToEthereum of storage ([#349](https://github.com/RequestNetwork/requestNetwork/issues/349)) ([1fea138](https://github.com/RequestNetwork/requestNetwork/commit/1fea138))
* Data access synchronization not parallelized ([#333](https://github.com/RequestNetwork/requestNetwork/issues/333)) ([cd63a22](https://github.com/RequestNetwork/requestNetwork/commit/cd63a22))
* Error block XXX not found ([#306](https://github.com/RequestNetwork/requestNetwork/issues/306)) ([6c9c59b](https://github.com/RequestNetwork/requestNetwork/commit/6c9c59b))
* Ethereum-storage meta, no redundant getPastEvents call ([#312](https://github.com/RequestNetwork/requestNetwork/issues/312)) ([28b5bb1](https://github.com/RequestNetwork/requestNetwork/commit/28b5bb1))
* Misc. minor fixes on the request node ([#334](https://github.com/RequestNetwork/requestNetwork/issues/334)) ([8fcf53d](https://github.com/RequestNetwork/requestNetwork/commit/8fcf53d))
* storage endless http request ([#284](https://github.com/RequestNetwork/requestNetwork/issues/284)) ([9adac9a](https://github.com/RequestNetwork/requestNetwork/commit/9adac9a))
* Storage Infura 1000 results error ([#320](https://github.com/RequestNetwork/requestNetwork/issues/320)) ([289a7f2](https://github.com/RequestNetwork/requestNetwork/commit/289a7f2))
* Use getSecondtLastBlockNumber instead of getLastBlockNumber for getBlockNumbersFromTimestamp ([#330](https://github.com/RequestNetwork/requestNetwork/issues/330)) ([58606b7](https://github.com/RequestNetwork/requestNetwork/commit/58606b7))


### Features

* add concurrent readMany to storage layer ([#363](https://github.com/RequestNetwork/requestNetwork/issues/363)) ([db3f484](https://github.com/RequestNetwork/requestNetwork/commit/db3f484))
* add IPFS peer for faster IPFS retrieval, and check IPFS and Ethereum nodes connections ([#353](https://github.com/RequestNetwork/requestNetwork/issues/353)) ([47358c2](https://github.com/RequestNetwork/requestNetwork/commit/47358c2))
* add logging interfaces and default logger ([#397](https://github.com/RequestNetwork/requestNetwork/issues/397)) ([f83a716](https://github.com/RequestNetwork/requestNetwork/commit/f83a716))
* add the ability to be able to configure the host + port via com… ([#355](https://github.com/RequestNetwork/requestNetwork/issues/355)) ([5b6a6c6](https://github.com/RequestNetwork/requestNetwork/commit/5b6a6c6))
* Add the two new IPFS nodes as known IPFS nodes ([#410](https://github.com/RequestNetwork/requestNetwork/issues/410)) ([b33f2e9](https://github.com/RequestNetwork/requestNetwork/commit/b33f2e9))
* additional node logs to show progress and logLevel option ([#338](https://github.com/RequestNetwork/requestNetwork/issues/338)) ([38559f4](https://github.com/RequestNetwork/requestNetwork/commit/38559f4))
* asynchronously pin IPFS files in batches ([#403](https://github.com/RequestNetwork/requestNetwork/issues/403)) ([926c22b](https://github.com/RequestNetwork/requestNetwork/commit/926c22b))
* check if the contracts are deployed and configured ([#360](https://github.com/RequestNetwork/requestNetwork/issues/360)) ([c18bf00](https://github.com/RequestNetwork/requestNetwork/commit/c18bf00))
* class to get Ethereum block information in storage ([#283](https://github.com/RequestNetwork/requestNetwork/issues/283)) ([1454981](https://github.com/RequestNetwork/requestNetwork/commit/1454981))
* configurable ethereum node host and port for smart contract deployment ([#358](https://github.com/RequestNetwork/requestNetwork/issues/358)) ([d7ad242](https://github.com/RequestNetwork/requestNetwork/commit/d7ad242))
* Create usable Dockerfile ([#278](https://github.com/RequestNetwork/requestNetwork/issues/278)) ([6c83f28](https://github.com/RequestNetwork/requestNetwork/commit/6c83f28))
* implements cached-throttle utility ([#348](https://github.com/RequestNetwork/requestNetwork/issues/348)) ([01c9885](https://github.com/RequestNetwork/requestNetwork/commit/01c9885))
* Migrate the synchronization from storage to data-access ([#292](https://github.com/RequestNetwork/requestNetwork/issues/292)) ([3d04d0d](https://github.com/RequestNetwork/requestNetwork/commit/3d04d0d))
* pin ipfs data on the node ([#361](https://github.com/RequestNetwork/requestNetwork/issues/361)) ([5830350](https://github.com/RequestNetwork/requestNetwork/commit/5830350))
* Save dataId's Ethereum metadata when append is called ([#352](https://github.com/RequestNetwork/requestNetwork/issues/352)) ([118d197](https://github.com/RequestNetwork/requestNetwork/commit/118d197))
* Storage cache for Ethereum metadata ([#323](https://github.com/RequestNetwork/requestNetwork/issues/323)) ([cb29b8e](https://github.com/RequestNetwork/requestNetwork/commit/cb29b8e))
* Storage get data from timestamp boundaries ([#291](https://github.com/RequestNetwork/requestNetwork/issues/291)) ([e9554cd](https://github.com/RequestNetwork/requestNetwork/commit/e9554cd))
* upgradable smart contracts ([#337](https://github.com/RequestNetwork/requestNetwork/issues/337)) ([c8cf724](https://github.com/RequestNetwork/requestNetwork/commit/c8cf724))


### Performance Improvements

* add the node ipfs request network at initialization ([#398](https://github.com/RequestNetwork/requestNetwork/issues/398)) ([7e0c25a](https://github.com/RequestNetwork/requestNetwork/commit/7e0c25a))
* faster initialization by factoring stat and read IPFS calls in one call ([#401](https://github.com/RequestNetwork/requestNetwork/issues/401)) ([184c14e](https://github.com/RequestNetwork/requestNetwork/commit/184c14e))






## [0.1.1-alpha.12](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.1.1-alpha.4...@requestnetwork/ethereum-storage@0.1.1-alpha.12) (2019-05-21)


### Bug Fixes

* block not found error in function addHashAndSizeToEthereum of storage ([#349](https://github.com/RequestNetwork/requestNetwork/issues/349)) ([1fea138](https://github.com/RequestNetwork/requestNetwork/commit/1fea138))
* Data access synchronization not parallelized ([#333](https://github.com/RequestNetwork/requestNetwork/issues/333)) ([cd63a22](https://github.com/RequestNetwork/requestNetwork/commit/cd63a22))
* Error block XXX not found ([#306](https://github.com/RequestNetwork/requestNetwork/issues/306)) ([6c9c59b](https://github.com/RequestNetwork/requestNetwork/commit/6c9c59b))
* Ethereum-storage meta, no redundant getPastEvents call ([#312](https://github.com/RequestNetwork/requestNetwork/issues/312)) ([28b5bb1](https://github.com/RequestNetwork/requestNetwork/commit/28b5bb1))
* Misc. minor fixes on the request node ([#334](https://github.com/RequestNetwork/requestNetwork/issues/334)) ([8fcf53d](https://github.com/RequestNetwork/requestNetwork/commit/8fcf53d))
* storage endless http request ([#284](https://github.com/RequestNetwork/requestNetwork/issues/284)) ([9adac9a](https://github.com/RequestNetwork/requestNetwork/commit/9adac9a))
* Storage Infura 1000 results error ([#320](https://github.com/RequestNetwork/requestNetwork/issues/320)) ([289a7f2](https://github.com/RequestNetwork/requestNetwork/commit/289a7f2))
* Use getSecondtLastBlockNumber instead of getLastBlockNumber for getBlockNumbersFromTimestamp ([#330](https://github.com/RequestNetwork/requestNetwork/issues/330)) ([58606b7](https://github.com/RequestNetwork/requestNetwork/commit/58606b7))


### Features

* add the ability to be able to configure the host + port via com… ([#355](https://github.com/RequestNetwork/requestNetwork/issues/355)) ([5b6a6c6](https://github.com/RequestNetwork/requestNetwork/commit/5b6a6c6))
* additional node logs to show progress and logLevel option ([#338](https://github.com/RequestNetwork/requestNetwork/issues/338)) ([38559f4](https://github.com/RequestNetwork/requestNetwork/commit/38559f4))
* class to get Ethereum block information in storage ([#283](https://github.com/RequestNetwork/requestNetwork/issues/283)) ([1454981](https://github.com/RequestNetwork/requestNetwork/commit/1454981))
* Create usable Dockerfile ([#278](https://github.com/RequestNetwork/requestNetwork/issues/278)) ([6c83f28](https://github.com/RequestNetwork/requestNetwork/commit/6c83f28))
* implements cached-throttle utility ([#348](https://github.com/RequestNetwork/requestNetwork/issues/348)) ([01c9885](https://github.com/RequestNetwork/requestNetwork/commit/01c9885))
* Migrate the synchronization from storage to data-access ([#292](https://github.com/RequestNetwork/requestNetwork/issues/292)) ([3d04d0d](https://github.com/RequestNetwork/requestNetwork/commit/3d04d0d))
* Save dataId's Ethereum metadata when append is called ([#352](https://github.com/RequestNetwork/requestNetwork/issues/352)) ([118d197](https://github.com/RequestNetwork/requestNetwork/commit/118d197))
* Storage cache for Ethereum metadata ([#323](https://github.com/RequestNetwork/requestNetwork/issues/323)) ([cb29b8e](https://github.com/RequestNetwork/requestNetwork/commit/cb29b8e))
* Storage get data from timestamp boundaries ([#291](https://github.com/RequestNetwork/requestNetwork/issues/291)) ([e9554cd](https://github.com/RequestNetwork/requestNetwork/commit/e9554cd))
* upgradable smart contracts ([#337](https://github.com/RequestNetwork/requestNetwork/issues/337)) ([c8cf724](https://github.com/RequestNetwork/requestNetwork/commit/c8cf724))






## [0.1.1-alpha.11](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.1.1-alpha.4...@requestnetwork/ethereum-storage@0.1.1-alpha.11) (2019-05-17)


### Bug Fixes

* Data access synchronization not parallelized ([#333](https://github.com/RequestNetwork/requestNetwork/issues/333)) ([cd63a22](https://github.com/RequestNetwork/requestNetwork/commit/cd63a22))
* Error block XXX not found ([#306](https://github.com/RequestNetwork/requestNetwork/issues/306)) ([6c9c59b](https://github.com/RequestNetwork/requestNetwork/commit/6c9c59b))
* Ethereum-storage meta, no redundant getPastEvents call ([#312](https://github.com/RequestNetwork/requestNetwork/issues/312)) ([28b5bb1](https://github.com/RequestNetwork/requestNetwork/commit/28b5bb1))
* Misc. minor fixes on the request node ([#334](https://github.com/RequestNetwork/requestNetwork/issues/334)) ([8fcf53d](https://github.com/RequestNetwork/requestNetwork/commit/8fcf53d))
* storage endless http request ([#284](https://github.com/RequestNetwork/requestNetwork/issues/284)) ([9adac9a](https://github.com/RequestNetwork/requestNetwork/commit/9adac9a))
* Storage Infura 1000 results error ([#320](https://github.com/RequestNetwork/requestNetwork/issues/320)) ([289a7f2](https://github.com/RequestNetwork/requestNetwork/commit/289a7f2))
* Use getSecondtLastBlockNumber instead of getLastBlockNumber for getBlockNumbersFromTimestamp ([#330](https://github.com/RequestNetwork/requestNetwork/issues/330)) ([58606b7](https://github.com/RequestNetwork/requestNetwork/commit/58606b7))


### Features

* additional node logs to show progress and logLevel option ([#338](https://github.com/RequestNetwork/requestNetwork/issues/338)) ([38559f4](https://github.com/RequestNetwork/requestNetwork/commit/38559f4))
* class to get Ethereum block information in storage ([#283](https://github.com/RequestNetwork/requestNetwork/issues/283)) ([1454981](https://github.com/RequestNetwork/requestNetwork/commit/1454981))
* Create usable Dockerfile ([#278](https://github.com/RequestNetwork/requestNetwork/issues/278)) ([6c83f28](https://github.com/RequestNetwork/requestNetwork/commit/6c83f28))
* implements cached-throttle utility ([#348](https://github.com/RequestNetwork/requestNetwork/issues/348)) ([01c9885](https://github.com/RequestNetwork/requestNetwork/commit/01c9885))
* Migrate the synchronization from storage to data-access ([#292](https://github.com/RequestNetwork/requestNetwork/issues/292)) ([3d04d0d](https://github.com/RequestNetwork/requestNetwork/commit/3d04d0d))
* Storage cache for Ethereum metadata ([#323](https://github.com/RequestNetwork/requestNetwork/issues/323)) ([cb29b8e](https://github.com/RequestNetwork/requestNetwork/commit/cb29b8e))
* Storage get data from timestamp boundaries ([#291](https://github.com/RequestNetwork/requestNetwork/issues/291)) ([e9554cd](https://github.com/RequestNetwork/requestNetwork/commit/e9554cd))






## [0.1.1-alpha.10](https://github.com/RequestNetwork/requestNetwork/compare/@requestnetwork/ethereum-storage@0.1.1-alpha.4...@requestnetwork/ethereum-storage@0.1.1-alpha.10) (2019-05-10)


### Bug Fixes

* Data access synchronization not parallelized ([#333](https://github.com/RequestNetwork/requestNetwork/issues/333)) ([cd63a22](https://github.com/RequestNetwork/requestNetwork/commit/cd63a22))
* Error block XXX not found ([#306](https://github.com/RequestNetwork/requestNetwork/issues/306)) ([6c9c59b](https://github.com/RequestNetwork/requestNetwork/commit/6c9c59b))
* Ethereum-storage meta, no redundant getPastEvents call ([#312](https://github.com/RequestNetwork/requestNetwork/issues/312)) ([28b5bb1](https://github.com/RequestNetwork/requestNetwork/commit/28b5bb1))
* Misc. minor fixes on the request node ([#334](https://github.com/RequestNetwork/requestNetwork/issues/334)) ([8fcf53d](https://github.com/RequestNetwork/requestNetwork/commit/8fcf53d))
* storage endless http request ([#284](https://github.com/RequestNetwork/requestNetwork/issues/284)) ([9adac9a](https://github.com/RequestNetwork/requestNetwork/commit/9adac9a))
* Storage Infura 1000 results error ([#320](https://github.com/RequestNetwork/requestNetwork/issues/320)) ([289a7f2](https://github.com/RequestNetwork/requestNetwork/commit/289a7f2))
* Use getSecondtLastBlockNumber instead of getLastBlockNumber for getBlockNumbersFromTimestamp ([#330](https://github.com/RequestNetwork/requestNetwork/issues/330)) ([58606b7](https://github.com/RequestNetwork/requestNetwork/commit/58606b7))


### Features

* class to get Ethereum block information in storage ([#283](https://github.com/RequestNetwork/requestNetwork/issues/283)) ([1454981](https://github.com/RequestNetwork/requestNetwork/commit/1454981))
* Create usable Dockerfile ([#278](https://github.com/RequestNetwork/requestNetwork/issues/278)) ([6c83f28](https://github.com/RequestNetwork/requestNetwork/commit/6c83f28))
* Migrate the synchronization from storage to data-access ([#292](https://github.com/RequestNetwork/requestNetwork/issues/292)) ([3d04d0d](https://github.com/RequestNetwork/requestNetwork/commit/3d04d0d))
* Storage cache for Ethereum metadata ([#323](https://github.com/RequestNetwork/requestNetwork/issues/323)) ([cb29b8e](https://github.com/RequestNetwork/requestNetwork/commit/cb29b8e))
* Storage get data from timestamp boundaries ([#291](https://github.com/RequestNetwork/requestNetwork/issues/291)) ([e9554cd](https://github.com/RequestNetwork/requestNetwork/commit/e9554cd))