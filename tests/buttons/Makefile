include ../Makefile.tests_common

FEATURES_REQUIRED += periph_gpio_irq
USEMODULE += xtimer

TEST_ON_CI_WHITELIST += all

include $(RIOTBASE)/Makefile.include

test:
	tests/01-run.py
