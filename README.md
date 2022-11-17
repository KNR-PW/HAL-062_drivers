# HAL-062_drivers

## NUCLEO H7XX

### BSP Library:
>**There are two section**:
> - Nucleo file - contains implementation of BSP library on Nucleo evaluation board
> - Common folder - contatins common modules for every evaluation board
---------------------------

### Lib folders:
> There are folders called Lib. It is neccessery to add them to project includes to be sure that every ".h" file is going to be shown for our project. Without that operation compiler wouldn't know where find our library's function.


### Components folder:
> There is possibility to add dedicated components for Nucleo board except that common one. However this library contains only basic commmon modules. Check on BSP library -> components to find more modules ( Need to know whitch one is available on your nucleo board )
