all:
	@echo "Build wc..."
	@ghc wc.hs -O3 -o main

global: all
	@mv main ../../wc.out
	@rm *.hi *.o 

clean:
	@echo "Clean.."
	@rm *.hi *.o main

