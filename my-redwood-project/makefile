
init:
	yarn create redwood-app app --typescript
	cd app && yarn install

mig:
	yarn rw prisma migrate dev

# generate the CRUD
g-sc:
	yarn redwood generate scaffold ${model}

g-cell:
	yarn rw generate cell ${name}

g-page:
	yarn rw generate page ${name}

g-layout:
	yarn rw generate layout ${name}

d-layout:
	yarn rw destroy layout ${name}

sb:
	yarn rw storybook


