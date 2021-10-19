# Versus

Programming challenge.

## Stories

* As Organizer I can invite members to Group, so that they can challenge each other in there skills.
* As Organizer I can create new Contest in Group, so other can try to complete it.
* As Organizer I can limit Contest period, so Members can see their result in some near future.

* As Member I can join Group using invitation, so I can challenge other members.
* As Member I can publish a Solution for an active Contest in my Group, so I can show my best skills and win Contest. 
* As Member I can vote for a next Contest, so the most interesting Contest is activated.
* As Member I can vote for someones Solution, to choose the best available Solution as winner.
* As Member I can see others members Score, to see most successful Members.

## API

### Create Group

```shell
curl -i -H "Authorization: Bearer ABC123..." \
     -d '{ \
           "name": "New logo" \
         }' \
    https://versus.example/api/groups
```
